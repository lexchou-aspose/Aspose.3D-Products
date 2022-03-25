---
title: Mengkonversi USDZ untuk OBJ via C# 
description: Mengkonversi USDZ & file 3D lainnya menggunakan .NET API
url: /id/net/conversion/usdz-to-obj/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: OBJ
otherformats: DXF RVM DRC FBX AMF OBJ 3MF GLTF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Mengkonversi USDZ untuk OBJ via C#" h2="Ekspor USDZ & file 3D lainnya menggunakan kerangka .NET, .NET Core dan Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Ekspor USDZ adegan sebagai OBJ dengan C#" %}}
1. Memuat berkas USDZ menggunakan konstruktor [Pemandangan indah](https://apireference.aspose.com/3d/net/aspose.threed/scene) Kelas2. Panggilan [Suasana. Simpan](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Metode
3. Berikan nama berkas keluaran dengan. Ekstensi obj sebagai parameter pertama
4. Tentukan 'WavefrontOBJ' nilai bidang dari [Format file](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Kelas
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Konversi Format API for .NET" %}}
Instal dari baris perintah sebagai "nuget instal Aspose.3d" "atau melalui konsol manajer paket Studio Visual dengan" paket instal Aspose.3D ".

Atau, dapatkan pemasang MSI offline atau DLLs dalam file ZIP dari [Unduhan](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# kode untuk USDZ untuk OBJ Konversi" gistPath="" %}}
```cs
// Muat USDZ dalam objek adegan 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// Simpan USDZ sebagai OBJ 
scene.Save("output.obj", Aspose.ThreeD.FileFormat.WavefrontOBJ);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}