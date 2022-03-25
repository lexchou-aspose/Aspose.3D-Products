---
title: USDZ 'i C# ile X'e dönüştürün 
description: USDZ ve diğer 3D dosyalarını .NET kullanarak dönüştürün
url: /tr/net/conversion/usdz-to-x/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: X
otherformats: HTML FBX STL DRC RVM DAE 3MF ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="USDZ \'i C# ile X\'e dönüştürün" h2=".NET Framework, .NET Core ve Mono kullanarak USDZ ve diğer 3D dosyalarını dışa aktar" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="USDZ Sahneyi C# ile X olarak dışa aktar" %}}
1. Bir kurucuyu kullanarak USDZ dosyasını yükleyin [Sahne](https://apireference.aspose.com/3d/net/aspose.threed/scene) Sınıf2. Çağrı [Sahne. Kaydet](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Yöntemi
3. Pass çıkış dosya adı ile. X uzantısı olarak ilk parametre olarak
4. 'XBinary' alan değerini belirtin [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Sınıf
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Biçim Dönüşümü API for .NET" %}}
Komut satırından ''nuget install Aspose.3d'' olarak veya ''Install-Package Aspose.3D'' ile Visual Studio Paket Yöneticisi Konsolu aracılığıyla yükleyin.

Alternatif olarak, bir ZIP dosyasında çevrimdışı MSI yükleyicisini veya DLL'leri alın [Indirmeler](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# USDZ için X\'e Dönüşüm Kodu" gistPath="" %}}
```cs
// Bir sahne nesnesine USDZ yükleyin 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// USDZ 'i X olarak kaydet 
scene.Save("output.x", Aspose.ThreeD.FileFormat.XBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}