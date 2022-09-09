---
title: แปลง USDZ เป็น PLY ผ่าน C# 
description: แปลงไฟล์ USDZ และ 3D อื่นๆ โดยใช้ .NET API
url: /th/net/conversion/usdz-to-ply/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: PLY
otherformats: AMF DRC HTML FBX DAE ASE JT RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="แปลง USDZ เป็น PLY ผ่าน C#" h2="ส่งออก USDZ และไฟล์ 3D อื่นๆ โดยใช้ .NET Framework, .NET Core และ Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ส่งออก USDZ ฉากเป็น PLY ด้วย C#" %}}
1. โหลดไฟล์ USDZ โดยใช้ตัวสร้างของ [ฉาก](https://apireference.aspose.com/3d/net/aspose.threed/scene) ระดับ2. โทร [ฉาก.บันทึก](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) กระบวนการ
3. ส่งชื่อไฟล์เอาต์พุตที่มีนามสกุล .ply เป็นพารามิเตอร์แรก
4. ระบุค่าฟิลด์ `PLY` จาก [รูปแบบไฟล์](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) ระดับ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D การแปลงรูปแบบ API for .NET" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget ติดตั้ง Aspose.3d``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.3D```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# โค้ดสำหรับการแปลง USDZ ถึง PLY" gistPath="" %}}
```cs
// โหลด USDZ ในวัตถุของ Scene 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// บันทึก USDZ เป็น PLY 
scene.Save("output.ply", Aspose.ThreeD.FileFormat.PLY);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}