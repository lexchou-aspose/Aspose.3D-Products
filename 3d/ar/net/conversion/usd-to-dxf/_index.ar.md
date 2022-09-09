---
title: تحويل USD إلى DXF عبر C# 
description: تحويل USD وملفات 3D أخرى باستخدام .NET API
url: /ar/net/conversion/usd-to-dxf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: DXF
otherformats: PLY AMF ASE HTML GLTF FBX DAE 3DS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل USD إلى DXF عبر C#" h2="تصدير USD وملفات 3D أخرى باستخدام .NET Framework و .NET Core و Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تصدير USD المشهد كـ DXF بـ C#" %}}
1. تحميل ملف USD باستخدام مُنشئ لـ [مشهد](https://apireference.aspose.com/3d/net/aspose.threed/scene) صف دراسي2. الاتصال [المشهد](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) طريقة
3. قم بتمرير اسم ملف الإخراج بامتداد .dxf كمعامل أول
4. حدد قيمة الحقل "DXF" من [تنسيق الملف](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) صف دراسي
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D تنسيق التحويل API for .NET" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.3d '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.3D ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# رمز التحويل من USD إلى DXF" gistPath="" %}}
```cs
// تحميل USD في كائن من المشهد 
var scene = new Aspose.ThreeD.Scene("template.usd");
// حفظ USD باسم DXF 
scene.Save("output.dxf", Aspose.ThreeD.FileFormat.DXF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}