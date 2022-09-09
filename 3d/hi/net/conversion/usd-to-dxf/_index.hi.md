---
title: C# के माध्यम से USD को DXF में बदलें 
description: .NET API का उपयोग करके USD और अन्य 3D फ़ाइलों को रूपांतरित करें
url: /hi/net/conversion/usd-to-dxf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: DXF
otherformats: PLY AMF ASE HTML GLTF FBX DAE 3DS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C# के माध्यम से USD को DXF में बदलें" h2=".NET फ्रेमवर्क, .NET कोर और Mono का उपयोग करके USD और अन्य 3D फ़ाइलें निर्यात करें" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# के साथ USD दृश्य को DXF के रूप में निर्यात करें" %}}
1. के कंस्ट्रक्टर का उपयोग करके USD फ़ाइल लोड करें [दृश्य](https://apireference.aspose.com/3d/net/aspose.threed/scene) कक्षा2. कॉल [दृश्य। सहेजें](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) तरीका
3. पहले पैरामीटर के रूप में .dxf एक्सटेंशन के साथ आउटपुट फ़ाइल नाम पास करें
4. से `DXF` फ़ील्ड मान निर्दिष्ट करें [फाइल प्रारूप](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) कक्षा
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D रूपांतरण प्रारूपित करें API for .NET" %}}
कमांड लाइन से ``nuget install Aspose.3d``` के रूप में या ```इंस्टॉल-पैकेज Aspose.3D``` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, ऑफ़लाइन MSI इंस्टॉलर या DLL को ZIP फ़ाइल से प्राप्त करें [डाउनलोड](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# USD से DXF रूपांतरण के लिए कोड" gistPath="" %}}
```cs
// सीन के ऑब्जेक्ट में USD लोड करें 
var scene = new Aspose.ThreeD.Scene("template.usd");
// USD को DXF के रूप में सहेजें 
scene.Save("output.dxf", Aspose.ThreeD.FileFormat.DXF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}