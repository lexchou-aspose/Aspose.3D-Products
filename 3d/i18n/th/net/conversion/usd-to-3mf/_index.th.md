---
title: แปลง USD TO 3MF Via C# 
description: แปลง USD & Other 3D Files using .NET API
url: /th/net/conversion/usd-to-3mf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: 3MF
otherformats: DAE STL JT GLTF RVM DXF PDF ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="แปลง USD TO 3MF Via C#" h2="Export USD & Other 3D Files using .NET Framework, .NET Core and Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export USD Scene AS 3MF with C#" %}}
1. โหลดไฟล์ USD โดยใช้ตัวสร้างของ [ฉาก](https://apireference.aspose.com/3d/net/aspose.threed/scene) คลาส2.โทร [ฉาก.บันทึก](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) วิธี
3.ผ่านเอาท์พุทชื่อไฟล์ที่มีนามสกุล.3mf เป็นพารามิเตอร์แรก
4.ระบุค่าฟิลด์ 'microsoft3mf' จาก [รูปแบบไฟล์](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) คลาส
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D FORMAT Conversion API for .NET" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น '''nuget ติดตั้ง Aspose.3d'''หรือผ่านทางคอนโซลผู้จัดการแพคเกจของ Visual Studio กับ'' 'install-Package Aspose.3D'''

หรือรับโปรแกรมติดตั้ง MSI แบบออฟไลน์หรือ dlls ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# รหัสสำหรับ USD ถึง 3MF การแปลง" gistPath="" %}}
```cs
// โหลด USD ในวัตถุของฉาก 
var scene = new Aspose.ThreeD.Scene("template.usd");
// บันทึก USD เป็น 3MF 
scene.Save("output.3mf", Aspose.ThreeD.FileFormat.Microsoft3MF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}