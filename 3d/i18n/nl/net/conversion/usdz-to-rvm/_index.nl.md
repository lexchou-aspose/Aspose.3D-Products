---
title: USDZ converteren naar RVM via C# 
description: USDZ en andere 3D bestanden converteren met .NET API
url: /nl/net/conversion/usdz-to-rvm/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: RVM
otherformats: DRC ASE 3MF AMF GLTF OBJ DXF RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="USDZ converteren naar RVM via C#" h2="Exporteer USDZ en andere 3D bestanden met .NET Framework, .NET Core en Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exporteer USDZ scene als RVM met C#" %}}
1. Laad USDZ bestand met behulp van een constructor van [Scène](https://apireference.aspose.com/3d/net/aspose.threed/scene) Klasse2. Bel [Scène. Opslaan](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Methode
3. Pass output bestandsnaam met. Rvm extensie als eerste parameter
4. Geef de veldwaarde 'RvmBinary' op vanaf [Bestandformaat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Klasse
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Formaatconversie API for .NET" %}}
Installeer vanaf de opdrachtregel als ''nuget install Aspose.3d'' of via Package Manager Console van Visual Studio met '''' Install-Package Aspose.3D''.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP bestand downloaden van [Downloads](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# code voor USDZ tot RVM conversie" gistPath="" %}}
```cs
// Laad de USDZ in een object van Scene 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// Bespaar USDZ als RVM 
scene.Save("output.rvm", Aspose.ThreeD.FileFormat.RvmBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}