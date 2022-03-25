---
title: Konvertera USD till JT via C# 
description: Konvertera USD & andra 3D filer med .NET API
url: /sv/net/conversion/usd-to-jt/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: JT
otherformats: OBJ DXF PLY PDF GLTF RVM FBX ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertera USD till JT via C#" h2="Exportera USD & andra 3D filer med .NET Ramverk, .NET kärna och Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportera USD scen som JT med C#" %}}
1. Ladda USD- filen med en konstruktor av [Scene](https://apireference.aspose.com/3d/net/aspose.threed/scene) Klass2. Utlysning [Scene.](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Metod
3. Pass output filnamn med . Jt utökning som första parametern
4. Ange 'SiemensJT9' fältvärde från 'SiemensJT9' [FilformatName](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Klass
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Formatkonvertering API for .NET" %}}
Installera från kommandorad som ''nuget install Aspose.3d''' eller via Package Manager Console of Visual Studio med ''' Installera-Package Aspose.3D'''.

Alternativt, hämta offline MSI-installatören eller DLL i en ZIP-fil från [Nerladdningar](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Kod för USD till JT konvertering" gistPath="" %}}
```cs
// Ladda USD i ett objekt i Scene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Spara USD som en JT 
scene.Save("output.jt", Aspose.ThreeD.FileFormat.SiemensJT9);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}