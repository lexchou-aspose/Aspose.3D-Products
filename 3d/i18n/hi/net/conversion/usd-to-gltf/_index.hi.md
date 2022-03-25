---
title: कन्वर्ट USD करने के लिए GLTF के माध्यम से C# 
description: कन्वर्ट USD और अन्य 3D फ़ाइलों का उपयोग .NET API
url: /hi/net/conversion/usd-to-gltf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: GLTF
otherformats: DRC GLTF FBX 3DS DAE RVM PDF JT 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="कन्वर्ट USD करने के लिए GLTF के माध्यम से C#" h2="निर्यात USD और अन्य 3D फ़ाइलों का उपयोग .NET ढांचे, .NET कोर और Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="निर्यात USD दृश्य के रूप में GLTF के साथ C#" %}}
1. लोड USD फ़ाइल का उपयोग कर के एक constructor [दृश्य](https://apireference.aspose.com/3d/net/aspose.threed/scene) वर्ग2. कॉल [दृश्य. Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) विधि
3. Pass आउटपुट फ़ाइल नाम के साथ. Gltf विस्तार के रूप में पहली पैरामीटर
4. निर्दिष्ट 'GLTF' क्षेत्र से मूल्य [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) वर्ग
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D प्रारूप रूपांतरण API for .NET" %}}
से स्थापित कमांड लाइन के रूप में '''nuget स्थापित Aspose.3d विजुअल स्टूडियो के लिए '''या के माध्यम से पैकेज प्रबंधक की कंसोल के साथ '''Install-पैकेज Aspose.3D के लिए'''.

वैकल्पिक रूप से, ऑफ़लाइन प्राप्त एमएसआई में संस्थापक या DLLs कार्यों के साथ एक ZIP से फ़ाइल [डाउनलोड](https://downloads.aspose.com/3d/net)है।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# कोड के लिए USD करने के लिए GLTF रूपांतरण" gistPath="" %}}
```cs
// लोड USD में एक वस्तु के दृश्य 
var scene = new Aspose.ThreeD.Scene("template.usd");
// बचाने USD के रूप में कार्यों के साथ एक GLTF 
scene.Save("output.gltf", Aspose.ThreeD.FileFormat.GLTF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}