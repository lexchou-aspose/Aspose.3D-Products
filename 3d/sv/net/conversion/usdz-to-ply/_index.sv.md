---
title: Konvertera USDZ till PLY via C# 
description: Konvertera USDZ och andra 3D filer med .NET API
url: /sv/net/conversion/usdz-to-ply/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: PLY
otherformats: AMF DRC HTML FBX DAE ASE JT RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertera USDZ till PLY via C#" h2="Exportera USDZ och andra 3D filer med .NET Framework, .NET Core och Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportera USDZ scen som PLY med C#" %}}
1. Ladda USDZ-fil med en konstruktor av [Scen](https://apireference.aspose.com/3d/net/aspose.threed/scene) klass2. Ring [Scene.Spara](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) metod
3. Skicka ut filnamnet med filtillägget .ply som första parameter
4. Ange "PLY"-fältvärdet från [Filformat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) klass
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Formatomvandling API for .NET" %}}
Installera från kommandoraden som ```nuget install Aspose.3d``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.3D```.

Alternativt kan du hämta offline-MSI-installationsprogrammet eller DLL-filerna i en ZIP-fil från [Nedladdningar](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Kod för omvandling från USDZ till PLY" gistPath="" %}}
```cs
// ladda USDZ i ett objekt av Scene 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// spara USDZ som en PLY 
scene.Save("output.ply", Aspose.ThreeD.FileFormat.PLY);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}