---
title: Ubah USD menjadi ASE melalui C# 
description: Konversi USD & file 3D lainnya menggunakan .NET API
url: /id/net/conversion/usd-to-ase/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: ASE
otherformats: ASE 3DS STL PLY GLTF DAE DRC HTML 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Ubah USD menjadi ASE melalui C#" h2="Ekspor USD & file 3D lainnya menggunakan .NET Framework, .NET Core, dan Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Ekspor USD Scene sebagai ASE dengan C#" %}}
1. Muat file USD menggunakan konstruktor dari [Tempat kejadian](https://apireference.aspose.com/3d/net/aspose.threed/scene) kelas2. Telepon [Adegan.Simpan](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) metode
3. Berikan nama file keluaran dengan ekstensi .ase sebagai parameter pertama
4. Tentukan nilai bidang `ASE` dari [Format File](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) kelas
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Konversi Format API for .NET" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.3d``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.3D```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [unduhan](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Kode untuk USD ke ASE Konversi" gistPath="" %}}
```cs
// memuat USD dalam objek Scene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// simpan USD sebagai ASE 
scene.Save("output.ase", Aspose.ThreeD.FileFormat.ASE);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}