---
title: تحويل USD إلى 3DS عبر C# 
description: تحويل USD وملفات 3D أخرى باستخدام .NET API
url: /ar/net/conversion/usd-to-3ds/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: 3DS
otherformats: OBJ STL HTML FBX RVM JT DAE DXF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل USD إلى 3DS عبر C#" h2="تصدير USD وملفات 3D أخرى باستخدام .NET Framework و .NET Core و Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تصدير USD المشهد كـ 3DS بـ C#" %}}
1. تحميل ملف USD باستخدام مُنشئ لـ [مشهد](https://apireference.aspose.com/3d/net/aspose.threed/scene) صف دراسي2. الاتصال [المشهد](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) طريقة
3. قم بتمرير اسم ملف الإخراج بامتداد .3ds كمعامل أول
4. حدد قيمة الحقل "Discreet3DS" من [تنسيق الملف](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) صف دراسي
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D تنسيق التحويل API for .NET" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.3d '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.3D ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# رمز التحويل من USD إلى 3DS" gistPath="" %}}
```cs
// تحميل USD في كائن من المشهد 
var scene = new Aspose.ThreeD.Scene("template.usd");
// حفظ USD باسم 3DS 
scene.Save("output.3ds", Aspose.ThreeD.FileFormat.Discreet3DS);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}