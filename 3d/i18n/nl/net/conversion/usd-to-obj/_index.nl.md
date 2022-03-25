---
title: USD converteren naar OBJ via C# 
description: USD en andere 3D bestanden converteren met .NET API
url: /nl/net/conversion/usd-to-obj/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: OBJ
otherformats: PDF FBX PLY RVM JT ASE HTML GLTF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="USD converteren naar OBJ via C#" h2="Exporteer USD en andere 3D bestanden met .NET Framework, .NET Core en Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exporteer USD scene als OBJ met C#" %}}
1. Laad USD bestand met behulp van een constructor van [Scène](https://apireference.aspose.com/3d/net/aspose.threed/scene) Klasse2. Bel [Scène. Opslaan](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Methode
3. Pass output bestandsnaam met. Obj extensie als eerste parameter
4. Geef de veldwaarde 'WavefrontOBJ' op vanaf [Bestandformaat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Klasse
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Formaatconversie API for .NET" %}}
Installeer vanaf de opdrachtregel als ''nuget install Aspose.3d'' of via Package Manager Console van Visual Studio met '''' Install-Package Aspose.3D''.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP bestand downloaden van [Downloads](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# code voor USD tot OBJ conversie" gistPath="" %}}
```cs
// Laad de USD in een object van Scene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Bespaar USD als OBJ 
scene.Save("output.obj", Aspose.ThreeD.FileFormat.WavefrontOBJ);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}