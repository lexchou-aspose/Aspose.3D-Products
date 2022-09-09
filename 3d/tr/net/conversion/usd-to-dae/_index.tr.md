---
title: C# aracılığıyla USD'i DAE'ye dönüştürün 
description: .NET API kullanarak USD ve diğer 3D dosyalarını dönüştürün
url: /tr/net/conversion/usd-to-dae/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: DAE
otherformats: FBX OBJ DXF HTML DAE STL RVM DRC 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C# aracılığıyla USD\'i DAE\'ye dönüştürün" h2=".NET Framework, .NET Core ve Mono kullanarak USD ve diğer 3D dosyalarını dışa aktarın" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# ile USD Sahneyi DAE olarak dışa aktar" %}}
1. Bir oluşturucu kullanarak USD dosyasını yükleyin [Sahne](https://apireference.aspose.com/3d/net/aspose.threed/scene) sınıf2. Çağrı [Sahne.Kaydet](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) yöntem
3. İlk parametre olarak .dae uzantılı çıktı dosyası adını iletin
4. Şuradan `Collada` alan değerini belirtin: [Dosya formatı](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) sınıf
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Biçim Dönüştürme API for .NET" %}}
Komut satırından ```nuget install Aspose.3d``` veya ```Install-Package Aspose.3D`` ile Visual Studio'nun Paket Yönetici Konsolu aracılığıyla yükleyin.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri şu adresten bir ZIP dosyasında alın: [İndirilenler](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="USD - DAE Dönüşümü için C# Kodu" gistPath="" %}}
```cs
// USD öğesini bir Sahne nesnesine yükleyin 
var scene = new Aspose.ThreeD.Scene("template.usd");
// USD'i DAE olarak kaydet 
scene.Save("output.dae", Aspose.ThreeD.FileFormat.Collada);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}