﻿---
title: تحويل USDZ إلى ASE عبر C# 
description: تحويل USDZ وملفات 3D أخرى باستخدام .NET API
url: /ar/net/conversion/usdz-to-ase/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: ASE
otherformats: PDF 3MF GLTF DRC DXF OBJ FBX DAE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل USDZ إلى ASE عبر C#" h2="تصدير USDZ وملفات 3D أخرى باستخدام .NET Framework و .NET Core و Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تصدير USDZ مشهد باسم ASE مع C#" %}}
1. تحميل USDZ ملف باستخدام مُنشئ [مشهد](https://apireference.aspose.com/3d/net/aspose.threed/scene) فئة2. اتصل [المشهد. حفظ](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) طريقة
3. تمرير اسم الملف الإخراج مع. تمديد ase كمعلمة أولى
4. تحديد قيمة الحقل "ASE" من [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) فئة
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D تنسيق التحويل API for .NET" %}}
قم بالتثبيت من سطر الأوامر باسم ''nuget install Aspose.3d'' أو عبر Package Manager Console of Visual Studio مع '''' تثبيت-حزمة Aspose.3D''.

بدلاً من ذلك ، احصل على مثبت MSI أو DLLs غير المتصل بالإنترنت في ملف ZIP من [التنزيلات](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# كود لـ USDZ إلى ASE تحويل" gistPath="" %}}
```cs
// تحميل USDZ في كائن من المشهد 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// احفظ USDZ كASE 
scene.Save("output.ase", Aspose.ThreeD.FileFormat.ASE);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}