---
title: Konvertera USD till DRC via C# 
description: Konvertera USD & andra 3D filer med .NET API
url: /sv/net/conversion/usd-to-drc/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: DRC
otherformats: PLY AMF DRC FBX RVM OBJ STL 3DS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertera USD till DRC via C#" h2="Exportera USD & andra 3D filer med .NET Ramverk, .NET kärna och Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportera USD scen som DRC med C#" %}}
1. Ladda USD- filen med en konstruktor av [Scene](https://apireference.aspose.com/3d/net/aspose.threed/scene) Klass2. Utlysning [Scene.](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Metod
3. Pass output filnamn med . Drc-utökning som första parametern
4. Ange fältvärde 'Draco' från [FilformatName](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Klass
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Formatkonvertering API for .NET" %}}
Installera från kommandorad som ''nuget install Aspose.3d''' eller via Package Manager Console of Visual Studio med ''' Installera-Package Aspose.3D'''.

Alternativt, hämta offline MSI-installatören eller DLL i en ZIP-fil från [Nerladdningar](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Kod för USD till DRC konvertering" gistPath="" %}}
```cs
// Ladda USD i ett objekt i Scene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Spara USD som en DRC 
scene.Save("output.drc", Aspose.ThreeD.FileFormat.Draco);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}