---
title: Converteer USD naar OBJ via C# 
description: Converteer USD en andere 3D bestanden met .NET API
url: /nl/net/conversion/usd-to-obj/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: OBJ
otherformats: PDF FBX PLY RVM JT ASE HTML GLTF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converteer USD naar OBJ via C#" h2="Exporteer USD en andere 3D bestanden met .NET Framework, .NET Core en Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exporteer USD Scene als OBJ met C#" %}}
1. Laad USD bestand met een constructor van [Tafereel](https://apireference.aspose.com/3d/net/aspose.threed/scene) klas2. Bel [Scène.Opslaan](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) methode
3. Geef de naam van het uitvoerbestand door met de extensie .obj als eerste parameter
4. Geef veldwaarde 'WavefrontOBJ' op van [Bestandsformaat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) klas
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Formaatconversie API for .NET" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.3d``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.3D```.

kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code voor USD naar OBJ conversie" gistPath="" %}}
```cs
// laad de USD in een object van Scene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// sla USD op als een OBJ 
scene.Save("output.obj", Aspose.ThreeD.FileFormat.WavefrontOBJ);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}