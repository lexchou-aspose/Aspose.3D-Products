---
title: C# 3D Formats Lithophane
url: /net/lithophane/
description: Create your Lithophane from image format jpg jpeg png tga bmp gif tiff via .NET library using a few lines of C# code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="3D Formats Lithophane Via C#" h2="Create your Lithophane from 3D document formats without any 3D modeling and rendering software to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
Developers can easily create your Lithophane using the 3D library. Few formats supported by the API are WavefrontOBJ, Discreet3DS, STL (ASCII, Binary), FBX (ASCII, Binary), Universal3D, Collada, GLB, glTF, PLY, DirectX, Google Draco formats, etc. The creation process is very simple, load the source file through an instance of the [scene class](https://apireference.aspose.com/3d/net/aspose.threed/scene), perform calculation operations on the Mesh object, and call with the relevant output The Save method of the format parameter.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Create your Lithophane from 3D Scene to various formats" %}}
Developers can easily create your Lithophane through the same process listed above. Consider some examples like **BMP to FBX lithophane**. Load BMP files through scene class objects. Create save options with [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxSaveOptions) to create save options and call the scene save method with the output file path and fbx options arguments. The API has appropriate options classes for saving into related classes, e.g. [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [Discreet3dsSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [Html5SaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) and more. Here is the full list of 3D [Lithophane formats](https://apireference.aspose.com/3d/net/aspose.threed.formats) options.

{{% blocks/products/pf/feature-page-code h3="C# Code for BMP to FBX Lithophane" %}}

```cs

//The original image that needs to be uploaded and the 3d file output after saving
string file = "template.bmp";
string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

//Create some new parameters
var td= TextureData.FromFile(file);
const float nozzleSize = 0.9f;//0.2mm
const float layerHeight = 0.2f;
var grayscale = ToGrayscale(td);
const float width = 120.0f;//canvas width is 200.0mm
float height = width / td.Width * td.Height;
float thickness = 10.0f;//10mm thickness
float layers = thickness / layerHeight;
int widthSegs = (int)Math.Floor(width / nozzleSize);
int heightSegs = (int)Math.Floor(height / nozzleSize);

//Perform computational operations on Mesh objects
var mesh = new Mesh();
for (int y = 0; y < heightSegs; y++)
{
    float dy = (float)y / heightSegs;
    for (int x = 0; x < widthSegs; x++)
    {
        float dx = (float)x / widthSegs;
        float gray = Sample(grayscale, td.Width, td.Height, dx, dy);
        float v = (1 - gray) * thickness;
        mesh.ControlPoints.Add(new Vector4(dx * width, dy * height, v));
    }
}
    for (int y = 0; y < heightSegs - 1; y++)
    {
        int row = (y * heightSegs);
        int ptr = row;
        for (int x = 0; x < widthSegs - 1; x++)
        {
            mesh.CreatePolygon(ptr, ptr + widthSegs, ptr + 1);
            mesh.CreatePolygon(ptr + 1, ptr + widthSegs, ptr + widthSegs + 1);
            ptr++;
        }
    }

//Generate 3d scene and save objects
var scene = new Scene(mesh);
scene.Save(output, FileFormat.FBX7400ASCII);

//The sample method to call
static float Sample(float[,] data, int w, int h, float x, float y)
{
    return data[(int)(x * w), (int)(y * h)];
}

//ToGrayscale method to call
static float[,] ToGrayscale(TextureData td)
{
    var ret = new float[td.Width, td.Height];
    var stride = td.Stride;
    var data = td.Data;
    var bytesPerPixel = td.BytesPerPixel;
    for (int y = 0; y < td.Height; y++)
    {
        int ptr = y * stride;
        for (int x = 0; x < td.Width; x++)
        {
            var v = (data[ptr] * 0.21f + data[ptr + 1] * 0.72f + data[ptr + 2] * 0.07f) / 255.0f;
            ret[x, y] = v;
            ptr += bytesPerPixel;
        }
    }
    return ret;
}

```

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options formats="all" afterslug="Lithophane" >}}