---
title: Ubah USDZ menjadi RVM melalui C# 
description: Konversi USDZ & file 3D lainnya menggunakan .NET API
url: /id/net/conversion/usdz-to-rvm/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: RVM
otherformats: DRC ASE 3MF AMF GLTF OBJ DXF RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Ubah USDZ menjadi RVM melalui C#" h2="Ekspor USDZ & file 3D lainnya menggunakan .NET Framework, .NET Core, dan Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Ekspor USDZ Scene sebagai RVM dengan C#" %}}
1. Muat file USDZ menggunakan konstruktor dari [Tempat kejadian](https://apireference.aspose.com/3d/net/aspose.threed/scene) kelas2. Telepon [Adegan.Simpan](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) metode
3. Berikan nama file keluaran dengan ekstensi .rvm sebagai parameter pertama
4. Tentukan nilai bidang `RvmBinary` dari [Format File](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) kelas
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Konversi Format API for .NET" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.3d``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.3D```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [unduhan](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Kode untuk USDZ ke RVM Konversi" gistPath="" %}}
```cs
// memuat USDZ dalam objek Scene 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// simpan USDZ sebagai RVM 
scene.Save("output.rvm", Aspose.ThreeD.FileFormat.RvmBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}