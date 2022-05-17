---
title: C# 3D Formats Watermark
url: /net/watermark/
description: Add Blind Watermark to 3D format 3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x via .NET library using a few lines of C# code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="3D Formats Watermark Via C#" h2="Add Blind Watermark to 3D document formats without any 3D modeling and rendering software to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
Developers can use the 3D library to add blind watermarks to 3D files. Few formats supported by the API are WavefrontOBJ, Discreet3DS, STL (ASCII, Binary), FBX (ASCII, Binary), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco formats, etc. The process of adding a blind watermark is very simple. Load the source file through the instance of [Scene Class](https://apireference.aspose.com/3d/net/aspose.threed/scene), and then implement the watermark through the EncodeWatermark method of the 3D library.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Add Blind Watermark to 3D Scene to various formats" %}}
Developers can easily add blind watermarks to 3d files through the same process listed above. Consider a few examples, such as **3DS to FBX watermark**. Load 3DS files through scene class objects. Create the saving options using [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxSaveOptions) to create save options and call the scene Save method with the output file path and fbx options as parameters. API has appropriate options classes for saving into relevant classes like [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions)  [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions)  [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions)  [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions)  [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) and more. Here is complete list for 3D [Watermark format](https://apireference.aspose.com/3d/net/aspose.threed.formats) options.

{{% blocks/products/pf/feature-page-code h3="C# Code for 3DS to FBX Watermark" %}}

```cs

//The source file that needs to be watermarked and the output file after saving
string file = "template.3ds";
string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

// create an instance of Scene
Scene scene = new Scene(file);

//Add watermark and password to files
var numMeshes = 0;
scene.RootNode.Accept((Node node) =>
{
    var mesh = node.GetEntity<Mesh>();
    if (mesh != null)
    {
        numMeshes++;
        mesh = Watermark.EncodeWatermark(mesh, "HelloWorld", "1234");
        if (mesh != null)
        {
            node.Entity = mesh;
        }
    }
    return true;
});

//Save the file in the format you want
scene.Save(output, FileFormat.FBX7400ASCII);

```

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Watermark" >}}