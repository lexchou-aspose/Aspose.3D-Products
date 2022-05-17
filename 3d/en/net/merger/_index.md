---
title: C# 3D Formats Merger
url: /net/merger/
description: Merge 3D format 3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x via .NET library using a few lines of C# code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="3D Formats Merger Via C#" h2="Merge 3D document formats without any 3D modeling and rendering software to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
Developers can easily merge 3D files using the 3D library. Few formats supported by the API are WavefrontOBJ, Discreet3DS, STL (ASCII, Binary), FBX (ASCII, Binary), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco formats, etc. The merging process is very simple. It processes the files to be merged in a loop, loads the usdz file through an instance of [scene class](https://apireference.aspose.com/3d/net/aspose.threed/scene), processes the usdz file and calls the file with The Save method for the relevant output format parameter.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Merge 3D Scene to various formats" %}}
Developers can easily merge 3d files through the same process listed above. Consider some examples like **3DS to FBX merger**. Load 3DS files via scene class objects. Create save options using [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxSaveOptions) to create save options and call the scene save method with the output file path and fbx options arguments. The API has appropriate options classes for saving into related classes, e.g. [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) and more. Here is the full list of 3D [merger formats](https://apireference.aspose.com/3d/net/aspose.threed.formats) options.

{{% blocks/products/pf/feature-page-code h3="C# Code for 3DS to FBX Merger" %}}
```cs

//Multiple source files that need to be merged
string[] files = {"template.3ds", "template2.3ds" };

//Process file merge to generate usdz file
Scene scene = new Scene();
int i = 0;
foreach (var file in files)
{
    using var fs = new FileStream(file, FileMode.Open, FileAccess.Read);
    FileFormat fmt = FileFormat.Detect(fs, files[i]);
    var subNode = scene.RootNode.CreateChildNode(files[i]);
    i++;
    try
    {
        Scene subScene = new Scene();
        var opt = fmt.CreateLoadOptions();
        subScene.Open(fs, opt);
        subNode.Entity = PolygonModifier.MergeMesh(subScene);
        MoveTo(subScene.RootNode, subNode);
    }
        catch (Exception)
        {
        }
}
var reviewFile = "result.usdz";
var usdz = new UsdSaveOptions(FileFormat.USDZ)
{
    PrimitiveToMesh = false,
    ExportMetaData = true
};
scene.Save(reviewFile, usdz);

//Process usdz files and save them in the format you want
var scene2 = new Scene();
var physicalFile = reviewFile;
using var fs2 = new FileStream(physicalFile, FileMode.Open, FileAccess.Read);
var fmt2 = FileFormat.Detect(fs2, "result");
var subScene2 = new Scene();
var opt2 = fmt2.CreateLoadOptions();
subScene2.Open(fs2, opt2);
var newNode = scene2.RootNode.CreateChildNode("");
double[] value = { 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1 };
newNode.Transform.TransformMatrix = new Matrix4(value);
MoveTo(subScene2.RootNode, newNode);
var output = "merger.fbx";
scene2.Save(output, FileFormat.FBX7400ASCII); 

//MoveTo class for call processing
public static void MoveTo(Node subScene, Node parent)
{
    while (subScene.ChildNodes.Count > 0)
    {
        var node = subScene.ChildNodes[0];
        subScene.ChildNodes.RemoveAt(0);
        parent.AddChildNode(node);
    }
}

```

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Merger" >}}