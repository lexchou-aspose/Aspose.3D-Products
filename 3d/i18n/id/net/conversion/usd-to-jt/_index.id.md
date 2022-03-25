---
title: Mengkonversi USD untuk JT via C# 
description: Mengkonversi USD & file 3D lainnya menggunakan .NET API
url: /id/net/conversion/usd-to-jt/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: JT
otherformats: OBJ DXF PLY PDF GLTF RVM FBX ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Mengkonversi USD untuk JT via C#" h2="Ekspor USD & file 3D lainnya menggunakan kerangka .NET, .NET Core dan Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Ekspor USD adegan sebagai JT dengan C#" %}}
1. Memuat berkas USD menggunakan konstruktor [Pemandangan indah](https://apireference.aspose.com/3d/net/aspose.threed/scene) Kelas2. Panggilan [Suasana. Simpan](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Metode
3. Berikan nama berkas keluaran dengan. Sambungan jt sebagai parameter pertama
4. Tentukan 'SiemensJT9' nilai bidang dari [Format file](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Kelas
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Konversi Format API for .NET" %}}
Instal dari baris perintah sebagai "nuget instal Aspose.3d" "atau melalui konsol manajer paket Studio Visual dengan" paket instal Aspose.3D ".

Atau, dapatkan pemasang MSI offline atau DLLs dalam file ZIP dari [Unduhan](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# kode untuk USD untuk JT Konversi" gistPath="" %}}
```cs
// Muat USD dalam objek adegan 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Simpan USD sebagai JT 
scene.Save("output.jt", Aspose.ThreeD.FileFormat.SiemensJT9);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}