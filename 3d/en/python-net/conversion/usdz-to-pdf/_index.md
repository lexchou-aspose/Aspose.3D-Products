---
title: Convert USDZ to PDF via Python 
description: Convert USDZ & other 3D files using .NET API
url: /python-net/conversion/usdz-to-pdf/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: PDF
otherformats: 3MF DRC DXF JT PLY GLTF FBX ASE 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert USDZ to PDF via Python" h2="Export USDZ & other 3D files using .NET Framework, .NET Core and Mono">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export USDZ Scene as PDF with C#" %}}
1. Load USDZ file using a from_file of [Scene](https://apireference.aspose.com/3d/python-net/aspose.threed/scene) class
2. Call [Scene.save](https://apireference.aspose.com/3d/python-net/aspose.threed/scene/methods/save/index) method
3. Pass output file name with .pdf extension as first parameter
4. Specify `PDF` field value from [FileFormat](https://apireference.aspose.com/3d/python-net/aspose.threed/fileformat/fields/index) class
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Format Conversion API for Python via .NET" %}}
Install from command line as ```pip install aspose-3d``` .

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/3d/python-net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code for USDZ to PDF Conversion" gistPath="" %}}
```cs
# load the USDZ in an object of Scene 
scene = aspose.threed.Scene.from_file("template.usdz");
# save USDZ as a PDF 
scene.save("output.pdf", aspose.threed.FileFormat.PDF);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
