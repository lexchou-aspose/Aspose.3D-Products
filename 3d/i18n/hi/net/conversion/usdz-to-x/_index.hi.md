---
title: कन्वर्ट USDZ X के माध्यम से करने के लिए C# 
description: कन्वर्ट USDZ और अन्य 3D फ़ाइलों का उपयोग .NET API
url: /hi/net/conversion/usdz-to-x/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: X
otherformats: HTML FBX STL DRC RVM DAE 3MF ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="कन्वर्ट USDZ X के माध्यम से करने के लिए C#" h2="निर्यात USDZ और अन्य 3D फ़ाइलों का उपयोग .NET ढांचे, .NET कोर और Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="निर्यात USDZ के साथ के रूप में दृश्य X C#" %}}
1. लोड USDZ फ़ाइल का उपयोग कर के एक constructor [दृश्य](https://apireference.aspose.com/3d/net/aspose.threed/scene) वर्ग2. कॉल [दृश्य. Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) विधि
3. Pass आउटपुट फ़ाइल नाम के साथ. एक्स एक्सटेंशन के रूप में पहली पैरामीटर
4. निर्दिष्ट 'XBinary' क्षेत्र से मूल्य [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) वर्ग
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D प्रारूप रूपांतरण API for .NET" %}}
से स्थापित कमांड लाइन के रूप में '''nuget स्थापित Aspose.3d विजुअल स्टूडियो के लिए '''या के माध्यम से पैकेज प्रबंधक की कंसोल के साथ '''Install-पैकेज Aspose.3D के लिए'''.

वैकल्पिक रूप से, ऑफ़लाइन प्राप्त एमएसआई में संस्थापक या DLLs कार्यों के साथ एक ZIP से फ़ाइल [डाउनलोड](https://downloads.aspose.com/3d/net)है।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# कोड के लिए USDZ X रूपांतरण करने के लिए" gistPath="" %}}
```cs
// लोड USDZ में एक वस्तु के दृश्य 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// बचाने USDZ के रूप में एक X 
scene.Save("output.x", Aspose.ThreeD.FileFormat.XBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}