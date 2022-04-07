---
title: "USD konvertálása JT-re a következőn keresztül: C# "
description: USD és egyéb 3D fájlok konvertálása a .NET API használatával
url: /hu/net/conversion/usd-to-jt/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: JT
otherformats: OBJ DXF PLY PDF GLTF RVM FBX ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="USD konvertálása JT-re a következőn keresztül: C#" h2="Exportáljon USD és egyéb 3D fájlokat a .NET Framework, a .NET Core és a Mono használatával" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="A(z) USD jelenet exportálása JT néven a(z) C# használatával" %}}
1. USD fájl betöltése a konstruktor használatával [Színhely](https://apireference.aspose.com/3d/net/aspose.threed/scene) osztály2. Hívjon [Jelenet.Mentés](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) módszer
3. Adja meg a kimeneti fájl nevét .jt kiterjesztéssel első paraméterként
4. Adja meg a SiemensJT9 mező értékét innen [Fájlformátum](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) osztály
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Formátumkonverzió API for .NET" %}}
Telepítés parancssorból ```nuget install Aspose.3d``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.3D``` paraméterrel.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket egy ZIP fájlban innen [letöltések](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Kód a(z) USD – JT konverzióhoz" gistPath="" %}}
```cs
// töltse be a(z) USD elemet a jelenet egyik objektumába 
var scene = new Aspose.ThreeD.Scene("template.usd");
// USD mentése JT-ként 
scene.Save("output.jt", Aspose.ThreeD.FileFormat.SiemensJT9);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}