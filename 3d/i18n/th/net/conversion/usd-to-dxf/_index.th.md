---
title: แปลง USD เป็น DXF ผ่าน C# 
description: แปลงไฟล์ USD และ 3D อื่นๆ โดยใช้ .NET API
url: /th/net/conversion/usd-to-dxf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: DXF
otherformats: PLY AMF ASE HTML GLTF FBX DAE 3DS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="แปลง USD เป็น DXF ผ่าน C#" h2="ส่งออก USD และไฟล์ 3D อื่นๆ โดยใช้ .NET Framework, .NET Core และ Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ส่งออก USD ฉากเป็น DXF ด้วย C#" %}}
1. โหลดไฟล์ USD โดยใช้ตัวสร้างของ [ฉาก](https://apireference.aspose.com/3d/net/aspose.threed/scene) ระดับ2. โทร [ฉาก.บันทึก](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) กระบวนการ
3. ส่งชื่อไฟล์เอาต์พุตที่มีนามสกุล .dxf เป็นพารามิเตอร์แรก
4. ระบุค่าฟิลด์ `DXF` จาก [รูปแบบไฟล์](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) ระดับ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D การแปลงรูปแบบ API for .NET" %}}
ติดตั้งจากบรรทัดคำสั่งเป็น ```nuget ติดตั้ง Aspose.3d``` หรือผ่าน Package Manager Console ของ Visual Studio ด้วย ```Install-Package Aspose.3D```

หรือรับตัวติดตั้ง MSI แบบออฟไลน์หรือ DLL ในไฟล์ ZIP จาก [ดาวน์โหลด](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# โค้ดสำหรับการแปลง USD ถึง DXF" gistPath="" %}}
```cs
// โหลด USD ในวัตถุของ Scene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// บันทึก USD เป็น DXF 
scene.Save("output.dxf", Aspose.ThreeD.FileFormat.DXF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}