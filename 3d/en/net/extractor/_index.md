---
title: C# 3D Formats Extract Assets
url: /net/extractor/
description: Extract Assets from 3D format 3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x via .NET library using a few lines of C# code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="3D Formats Extract Assets Via C#" h2="Extract Assets from 3D document formats without any 3D modeling and rendering software to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
Developers can use the 3D library to easily extract 3D file assets. Few formats supported by the API are WavefrontOBJ, Discreet3DS, STL (ASCII, Binary), FBX (ASCII, Binary), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco formats, etc. The extraction process is simple, load the source file through an instance of the [scene class](https://apireference.aspose.com/3d/net/aspose.threed/scene), create the archive class and handle the extraction asset class, and call the The Save method for the relevant output format parameter.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Extract Assets from 3D Scene to various formats" %}}
Developers can easily extract assets from 3d files through the same process listed above. Consider some examples like **3DS to FBX Extractor**. Load 3DS files via scene class objects. Create save options with [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxSaveOptions) to create save options and call the scene save method with the output file path and fbx options arguments. The API has appropriate options classes for saving into related classes, e.g. [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) and more. Here is the full list of 3D [extract formats](https://apireference.aspose.com/3d/net/aspose.threed.formats) options.

{{% blocks/products/pf/feature-page-code h3="C# Code for 3DS to FBX Extract Assets" %}}

```cs

//Source files that need to extract assets
string file = "template.3ds";
Scene scene = new Scene(file);  

//The output is in a compressed file format, and Directory represents the name of an existing folder
var zipOutput = Path.Combine("Directory", "OutputFile.zip");
using var output = new FileStream(zipOutput, FileMode.Create);
using var za = new Zip(output);

//Call the Extract method to perform asset extraction operations
Extract(scene,za,true);

//Callable Extract method,The parameter texture indicates: whether to extract the texture
private void Extract(Scene scene, Zip za,bool texture)
{
    var extractor = new Extractor(za,texture);
    extractor.Extract(scene);
}

//Create a compressed file processing class
class Zip : IDisposable
{
    private ZipArchive archive;
    private HashSet<string> entries = new HashSet<string>();
    public Zip(Stream stream)
    {
        archive = new ZipArchive(stream, ZipArchiveMode.Create);
    }
    public void Dispose()
    {
        archive.Dispose();
    }
    public void Add(string fileName, byte[] content, bool enableCompression)
    {
        var entryName = PickName(fileName);
        var compressionLevel = enableCompression ? CompressionLevel.Fastest : CompressionLevel.NoCompression;
        var entry = archive.CreateEntry(entryName, compressionLevel);
        using var stream = entry.Open();
        stream.Write(content, 0, content.Length);
    }
    private string PickName(string fileName)
    {
        if (!entries.Contains(fileName))
        {
            entries.Add(fileName);
            return fileName;
        }
        var baseName = Path.GetFileNameWithoutExtension(fileName);
        var ext = Path.GetExtension(fileName);
        for (var idx = 2; ; idx++)
        {
            var newName = baseName + "_" + idx;
            if (!string.IsNullOrEmpty(ext))
                newName += ext;
            if (entries.Contains(newName))
                continue;
            entries.Add(newName);
            return newName;
        }
    }
}

//Create an asset extraction processing class
class Extractor
{
    private Zip zip;
    private bool texture;
    HashSet<A3DObject> visited = new HashSet<A3DObject>();
    public Extractor(Zip zip,bool texture)
    {
        this.zip = zip;
        this.texture = texture;
    }
    private bool CanVisit(A3DObject obj)
    {
        if (visited.Contains(obj))
            return false;
        visited.Add(obj);
        return true;
    }
    public void Extract(Scene scene)
    {
        if (scene.Library != null && scene.Library.Count > 0)
        {
            foreach (var obj in scene.Library)
            {
                Visit(obj);
            }
        }
        VisitNode(scene.RootNode);
    }
    private void VisitNode(Node node)
    {
        if (!CanVisit(node))
            return;
        if (texture)
        {
            foreach (var mat in node.Materials)
            {
                VisitMaterial(mat);
            }
        }
        foreach (var entity in node.Entities)
        {
            if (entity is Mesh)
                Save((Mesh)entity, node.Name);
        }
        foreach (var child in node.ChildNodes)
        {
            VisitNode(child);
        }
    }
    private void VisitMaterial(Material mat)
    {
        if (!CanVisit(mat))
            return;
        if (!texture)
            return;
        foreach (var tslot in mat)
        {
            if (tslot.Texture is Texture)
            {
                Save((Texture)tslot.Texture);
            }
        }
    }
    private void Visit(A3DObject obj)
    {
        if (texture && obj is Texture)
        {
            Save((Texture)obj);
        }
        else if (obj is Mesh)
        {
            Save((Mesh)obj, null);
        }
        else if (obj is Node)
        {
            VisitNode((Node)obj);
        }
    }
    private void Save(Mesh mesh, string? nodeName)
    {
        if (!CanVisit(mesh))
            return;
        Scene scene = new Scene(mesh);
        using (var ms = new MemoryStream())
        {
            scene.Save(ms, FileFormat.FBX7400ASCII);
            var name = nodeName;
            if (string.IsNullOrEmpty(name))
                name = mesh.Name;
            if (string.IsNullOrEmpty(name))
                name = "mesh";
            var ext = ".fbx";
            zip.Add(name + ext, ms.ToArray(), true);
        }
    }
    private void Save(Texture tex)
    {
        if (tex.Content == null || !CanVisit(tex))
            return;
        var fileName = tex.FileName != null ? Path.GetFileName(tex.FileName) : null;
        zip.Add(fileName, tex.Content, false);
    }
}

```

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Extractor" >}}