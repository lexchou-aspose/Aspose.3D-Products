---
title: Convert USDZ to DRC via Python 
description: Convert USDZ & other 3D files using .NET API
url: /python-net/conversion/usdz-to-drc/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: DRC
otherformats: FBX RVM OBJ PLY PDF STL DRC GLTF 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert USDZ to DRC via Python" h2="Export USDZ & other 3D files using .NET Framework, .NET Core and Mono">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export USDZ Scene as DRC with C#" %}}
1. Load USDZ file using a from_file of [Scene](https://apireference.aspose.com/3d/python-net/aspose.threed/scene) class
2. Call [Scene.save](https://apireference.aspose.com/3d/python-net/aspose.threed/scene/methods/save/index) method
3. Pass output file name with .drc extension as first parameter
4. Specify `Draco` field value from [FileFormat](https://apireference.aspose.com/3d/python-net/aspose.threed/fileformat/fields/index) class
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Format Conversion API for Python via .NET" %}}
Install from command line as ```pip install aspose-3d``` .

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/3d/python-net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code for USDZ to DRC Conversion" gistPath="" %}}
```cs
# load the USDZ in an object of Scene 
scene = aspose.threed.Scene.from_file("template.usdz");
# save USDZ as a DRC 
scene.save("output.drc", aspose.threed.FileFormat.Draco);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}