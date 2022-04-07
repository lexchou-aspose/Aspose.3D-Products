---
title: تحويل USDZ إلى DAE عبر C# 
description: تحويل USDZ وملفات 3D أخرى باستخدام .NET API
url: /ar/net/conversion/usdz-to-dae/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: DAE
otherformats: DRC HTML DAE ASE STL PLY 3MF OBJ 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل USDZ إلى DAE عبر C#" h2="تصدير USDZ وملفات 3D أخرى باستخدام .NET Framework و .NET Core و Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تصدير USDZ المشهد كـ DAE بـ C#" %}}
1. تحميل ملف USDZ باستخدام مُنشئ لـ [مشهد](https://apireference.aspose.com/3d/net/aspose.threed/scene) صف دراسي2. الاتصال [المشهد](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) طريقة
3. قم بتمرير اسم ملف الإخراج بامتداد .dae كمعامل أول
4. حدد قيمة الحقل "Collada" من [تنسيق الملف](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) صف دراسي
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D تنسيق التحويل API for .NET" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.3d '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.3D ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التحميلات](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# رمز التحويل من USDZ إلى DAE" gistPath="" %}}
```cs
// تحميل USDZ في كائن من المشهد 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// حفظ USDZ باسم DAE 
scene.Save("output.dae", Aspose.ThreeD.FileFormat.Collada);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}