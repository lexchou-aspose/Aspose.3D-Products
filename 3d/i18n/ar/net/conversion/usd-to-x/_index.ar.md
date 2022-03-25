---
title: تحويل USD إلى X عبر C# 
description: تحويل USD وملفات 3D أخرى باستخدام .NET API
url: /ar/net/conversion/usd-to-x/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: X
otherformats: PLY FBX AMF ASE 3DS JT HTML STL 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل USD إلى X عبر C#" h2="تصدير USD وملفات 3D أخرى باستخدام .NET Framework و .NET Core و Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تصدير USD مشهد كX مع C#" %}}
1. تحميل USD ملف باستخدام مُنشئ [مشهد](https://apireference.aspose.com/3d/net/aspose.threed/scene) فئة2. اتصل [المشهد. حفظ](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) طريقة
3. تمرير اسم الملف الإخراج مع. تمديد x كمعلمة أولى
4. حدد قيمة الحقل "XBinary" من [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) فئة
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D تنسيق التحويل API for .NET" %}}
قم بالتثبيت من سطر الأوامر باسم ''nuget install Aspose.3d'' أو عبر Package Manager Console of Visual Studio مع '''' تثبيت-حزمة Aspose.3D''.

بدلاً من ذلك ، احصل على مثبت MSI أو DLLs غير المتصل بالإنترنت في ملف ZIP من [التنزيلات](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# رمز لـ USD إلى X Conversation" gistPath="" %}}
```cs
// تحميل USD في كائن من المشهد 
var scene = new Aspose.ThreeD.Scene("template.usd");
// حفظ USD كعلامة X 
scene.Save("output.x", Aspose.ThreeD.FileFormat.XBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}