﻿---
title: แปลง 3MF เป็น AMF ผ่าน C# 
weight: 750
url: /th/net/conversion/3mf-to-amf/ 
description: โค้ดตัวอย่างสำหรับการแปลง 3MF ถึง AMF C# ใช้ API โค้ดตัวอย่างสำหรับแบตช์ 3MF ไฟล์เป็น AMF การแปลงภายใน VB.NET, Asp.NET หรือแอปพลิเคชันตาม .NET ใดๆ
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง 3MF เป็น AMF ผ่าน C#" h2="แสดงผล 3MF เป็น AMF โดยไม่ต้องใช้ซอฟต์แวร์สร้างแบบจำลองและการแสดงผล 3D" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="AMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3MF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง 3MF เป็น AMF โดยใช้ C#" %}}

 ในการแปลง 3MF เป็น AMF เราจะใช้
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API ซึ่งเป็นการจัดการและการแปลงเอกสารที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย API สำหรับแพลตฟอร์ม C# เปิด
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 package manager ค้นหา
 Aspose.3D 
 และติดตั้ง คุณยังสามารถใช้คำสั่งต่อไปนี้จาก Package Manager Console

{{% blocks/products/pf/agp/code-block title="คำสั่งคอนโซลตัวจัดการแพ็คเกจ" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง 3MF เป็น AMF ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

 โปรแกรมเมอร์ .NET สามารถโหลดและแปลงไฟล์ 3MF เป็น AMF ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ 3MF ผ่านตัวสร้างของ Scene class1. สร้างอินสแตนซ์ของ AmfSaveOptions1. ตั้งค่า AMF คุณสมบัติเฉพาะสำหรับการแปลงขั้นสูง1. เรียกวิธี Scene.Save1. ส่งเส้นทางเอาต์พุตด้วย AMF นามสกุลไฟล์ & อ็อบเจ็กต์ของ AmfSaveOptions1. ตรวจสอบไฟล์ผลลัพธ์ AMF ที่เส้นทางที่ระบุ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ด Conversion .NET ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Mono- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio- Aspose.3D for .NET DLL ที่อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="โค้ดตัวอย่างนี้แสดงการแปลง 3MF ถึง AMF C#" offSpacer="" %}}

```cs
// โหลด 3MF ในวัตถุของ Scene 
var document = new Aspose.ThreeD.Scene("template.3mf");
// สร้างอินสแตนซ์ของ AmfSaveOptions 
var options = new Aspose.ThreeD.Formats.AmfSaveOptions();
// บันทึก 3MF เป็น AMF 
document.Save("output.amf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="แอปฟรีสำหรับแปลง 3MF เป็น AMF" sectionDescription="ตรวจสอบการสาธิตสดของเราสำหรับ [3MF เป็น AMF แปลง](https://products.aspose.app/3d/conversion/3mf-to-amf) พร้อมสิทธิประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไร" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ 3MF ของคุณแล้วกดปุ่ม \"แปลง\"" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงก์ดาวน์โหลดสำหรับไฟล์ผลลัพธ์ AMF ทันที" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D ไลบรารีการประมวลผลไฟล์เพื่อจัดการไฟล์ 3D โดยไม่ต้องใช้ซอฟต์แวร์สร้างแบบจำลองและแสดงผล 3D API รองรับ Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, รูปแบบไฟล์ PLY, DirectX, Google Draco และอีกมากมาย นักพัฒนาสามารถสร้าง อ่าน แปลง แก้ไข และควบคุมเนื้อหาของรูปแบบเอกสาร 3D รูปแบบได้อย่างง่ายดาย



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3MF" readMoreLink="https://docs.fileformat.com/3d/3mf/" >}}
3MF, 3D รูปแบบการผลิต ถูกใช้โดยแอปพลิเคชันเพื่อแสดงโมเดลอ็อบเจ็กต์ 3D ให้กับแอปพลิเคชัน แพลตฟอร์ม บริการ และเครื่องพิมพ์อื่นๆ ที่หลากหลาย สร้างขึ้นเพื่อหลีกเลี่ยงข้อจำกัดและปัญหาในรูปแบบไฟล์ 3D อื่นๆ เช่น STL สำหรับการทำงานกับเครื่องพิมพ์ 3D เวอร์ชันล่าสุด 3MF ค่อนข้างเป็นรูปแบบไฟล์ใหม่ที่ได้รับการพัฒนาและเผยแพร่โดยกลุ่ม 3MF มีเนื้อหาเพียงพอที่จะอธิบายแบบจำลอง เก็บข้อมูลภายใน สี และคุณลักษณะอื่นๆ ที่ทำให้ขยายได้เพื่อรองรับนวัตกรรมใหม่ในการพิมพ์ 3D รูปแบบนี้ขยายได้ นำไปใช้ในวงกว้างและไม่มีปัญหาที่รุมเร้ารูปแบบไฟล์อื่นๆ ที่ใช้กันอย่างแพร่หลาย

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="amf" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}
รูปแบบไฟล์ Additive Manufacturing (AMF) กำหนดมาตรฐานเปิดสำหรับคำอธิบายออบเจ็กต์เพื่อใช้ในกระบวนการผลิตแบบเติมแต่ง เช่น 3D การพิมพ์ โปรแกรม CAD ใช้รูปแบบไฟล์ AMF โดยใช้ข้อมูล เช่น เรขาคณิต สี และวัสดุของวัตถุ AMF แตกต่างจากรูปแบบ STL เนื่องจากด้านข้างไม่รองรับสี วัสดุ โครงตาข่าย และกลุ่มดาว

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง 3MF เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-3ds/" name="3MF ถึง 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-dae/" name="3MF ถึง DAE" description="การแลกเปลี่ยนสินทรัพย์ดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-fbx/" name="3MF ถึง FBX" description="3D รูปแบบ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-html/" name="3MF ถึง HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-obj/" name="3MF ถึง OBJ" description="3D รูปแบบไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-pdf/" name="3MF ถึง PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-ply/" name="3MF ถึง PLY" description="รูปแบบไฟล์รูปหลายเหลี่ยม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-rvm/" name="3MF ถึง RVM" description="โมเดลการออกแบบโรงงาน AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-stl/" name="3MF ถึง STL" description="เปลี่ยนได้ 3D เรขาคณิตพื้นผิว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3mf-to-u3d/" name="3MF ถึง U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}