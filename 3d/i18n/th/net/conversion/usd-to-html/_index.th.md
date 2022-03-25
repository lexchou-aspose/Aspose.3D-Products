---
title: แปลง USD TO HTML Via C# 
description: แปลง USD & Other 3D Files using .NET API
url: /th/net/conversion/usd-to-html/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: HTML
otherformats: PLY PDF RVM JT ASE DXF DAE FBX 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="แปลง USD TO HTML Via C#" h2="Export USD & Other 3D Files using .NET Framework, .NET Core and Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export USD Scene AS HTML with C#" %}}
1. โหลดไฟล์ USD โดยใช้ตัวสร้างของ [ฉาก](https://apireference.aspose.com/3d/net/aspose.threed/scene) คลาส2.โทร [ฉาก.บันทึก](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) วิธี
3.ผ่านเอาท์พุทชื่อไฟล์ด้วยส่วนขยาย HTML เป็นพารามิเตอร์แรก
4.ระบุ 'HTML5' ค่าฟิลด์จาก [รูปแบบไฟล์](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) คลาส
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D FORMAT Conversion API for .NET" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น '''nuget ติดตั้ง Aspose.3d'''หรือผ่านทางคอนโซลผู้จัดการแพคเกจของ Visual Studio กับ'' 'install-Package Aspose.3D'''

หรือรับโปรแกรมติดตั้ง MSI แบบออฟไลน์หรือ dlls ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# รหัสสำหรับ USD ถึง HTML การแปลง" gistPath="" %}}
```cs
// โหลด USD ในวัตถุของฉาก 
var scene = new Aspose.ThreeD.Scene("template.usd");
// บันทึก USD เป็น HTML 
scene.Save("output.html", Aspose.ThreeD.FileFormat.HTML5);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}