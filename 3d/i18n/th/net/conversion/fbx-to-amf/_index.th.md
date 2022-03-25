﻿---
title: แปลง FBX TO AMF Via C# 
weight: 400
url: /th/net/conversion/fbx-to-amf/ 
description: ตัวอย่างรหัสสำหรับ FBX ถึง AMF C# การแปลงใช้โค้ดตัวอย่าง API สำหรับไฟล์ batch FBX เป็น AMF การแปลงภายใน VB.NET, ASP .NET หรือแอพพลิเคชันที่ใช้ .NET
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง FBX TO AMF Via C#" h2="Render FBX AS AMF โดยไม่มีการสร้างแบบจำลอง 3D และซอฟต์แวร์การแสดงผล" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="AMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to convert FBX TO AMF การใช้ C#" %}}

 เพื่อที่จะแปลง FBX เป็น AMF เราจะใช้
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API ซึ่งเป็นคุณลักษณะที่อุดมไปด้วยที่มีประสิทธิภาพและง่ายต่อการใช้การจัดการเอกสารและการแปลง API สำหรับ C# แพลตฟอร์มเปิด
 [Nuget](https://www.nuget.org/packages/aspose.3d) 
 ผู้จัดการแพคเกจค้นหา
 Aspose.3D 
 และติดตั้งนอกจากนี้คุณยังสามารถใช้คำสั่งต่อไปนี้จากคอนโซลผู้จัดการแพคเกจ

{{% blocks/products/pf/agp/code-block title="ผู้จัดการแพคเกจคำสั่งคอนโซล" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps TO convert FBX TO AMF Via C# [ตัวอย่าง]" %}}

{{% blocks/products/pf/agp/text %}}

 .NET โปรแกรมเมอร์สามารถโหลดและแปลง FBX ไฟล์ AMF ในเพียงไม่กี่บรรทัดของรหัส

{{% /blocks/products/pf/agp/text %}}

1. โหลด FBX ไฟล์ผ่านตัวสร้างชั้นฉาก1. สร้างอินสแตนซ์ของ amfsaveoptions1. ตั้งค่า AMF คุณสมบัติเฉพาะสำหรับการแปลงขั้นสูง1. เรียกฉากบันทึกวิธี1. ผ่านเส้นทางเอาต์พุตด้วย AMF นามสกุลไฟล์และวัตถุของ amfsaveoptions1. ตรวจสอบผลลัพธ์ AMF ไฟล์ที่เส้นทางที่ระบุ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนที่จะใช้รหัสการแปลง .NET โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Mono- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio.- Aspose.3D for .NET DLL อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="รหัสตัวอย่างนี้แสดง FBX เป็น AMF C# การแปลง" offSpacer="" %}}

```cs
// โหลด FBX ในวัตถุของฉาก 
var document = new Aspose.ThreeD.Scene("template.fbx");
// สร้างอินสแตนซ์ของ amfsaveoptions 
var options = new Aspose.ThreeD.Formats.AmfSaveOptions();
// บันทึก FBX เป็น AMF 
document.Save("output.amf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Free APP TO convert FBX TO AMF" sectionDescription="ตรวจสอบการสาธิตสดของเราสำหรับ [FBX TO AMF Conversion](https://products.aspose.app/3d/conversion/fbx-to-amf) ที่มีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไร" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงแค่อัปโหลดไฟล์ FBX ของคุณและกดปุ่ม \"แปลง\"" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงก์ดาวน์โหลดสำหรับไฟล์ AMF" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D ไลบรารีการประมวลผลไฟล์เพื่อจัดการ 3D ไฟล์โดยไม่มีการสร้างแบบจำลองและซอฟต์แวร์การแสดงผลใดๆ 3D API รองรับ Discreet3DS, WavefrontOBJ, FBX (ASCII, binary), STL (ASCII, binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco รูปแบบไฟล์และอื่นๆนักพัฒนาสามารถสร้างอ่านแปลงแก้ไขและควบคุมเนื้อหาของ 3D รูปแบบเอกสารได้อย่างง่ายดาย



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, filmbox เป็นรูปแบบไฟล์ 3D ที่ได้รับความนิยมซึ่งพัฒนาขึ้นโดย kaydara สำหรับ motionbuilder Autodesk Inc ในปี2006และเป็นหนึ่งในรูปแบบการแลกเปลี่ยนหลัก 3D ที่ใช้โดยเครื่องมือ 3D FBX สามารถใช้ได้ทั้งในรูปแบบไฟล์ไบนารีและ ASCII. รูปแบบนี้ได้รับการจัดตั้งขึ้นเพื่อให้สามารถทำงานร่วมกันระหว่างแอพพลิเคชันการสร้างเนื้อหาดิจิทัลได้มีเครื่องมือมากมายสำหรับการแปลงจาก/เป็น FBX รูปแบบไฟล์

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="amf" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}
รูปแบบไฟล์การผลิตสารเติมแต่ง (AMF) กำหนดมาตรฐานเปิดสำหรับคำอธิบายวัตถุเพื่อที่จะใช้โดยกระบวนการผลิตสารเติมแต่งเช่น 3D การพิมพ์ CAD โปรแกรมใช้รูปแบบไฟล์ AMF โดยการใช้ข้อมูลเช่นเรขาคณิตสีและวัสดุของวัตถุ AMF แตกต่างจากรูปแบบ STL เนื่องจากด้านข้างไม่สนับสนุนสีวัสดุโปรยและกลุ่มดาว

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงที่สนับสนุนอื่นๆ" subTitle="FBX ลงในรูปแบบไฟล์อื่นๆอีกมากมายรวมทั้งไม่กี่รายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-3ds/" name="FBX TO 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-dae/" name="FBX TO DAE" description="การแลกเปลี่ยนสินทรัพย์ดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-html/" name="FBX TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-obj/" name="FBX TO OBJ" description="3D รูปแบบไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-pdf/" name="FBX TO PDF" description="รูปแบบเอกสารแบบพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-ply/" name="FBX TO PLY" description="รูปแบบไฟล์รูปหลายเหลี่ยม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-rvm/" name="FBX TO RVM" description="Aveva รุ่น Plant Design" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-stl/" name="FBX TO STL" description="เปลี่ยนได้ 3D เรขาคณิตพื้นผิว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/fbx-to-u3d/" name="FBX TO U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}