﻿---
title: แปลง GLB เป็น PDF ผ่าน Java
weight: 530
url: /th/java/conversion/glb-to-pdf/ 
description: ตัวอย่างโค้ดการแปลง Java สำหรับรูปแบบ GLB เป็นไฟล์ PDF ใช้โค้ดตัวอย่างนี้เพื่อแปลง GLB เป็น PDF ภายในแอปพลิเคชันบนเว็บหรือเดสก์ท็อป Java
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง GLB เป็น PDF ผ่าน Java" h2="การแปลง GLB เป็น PDF โดยใช้ไลบรารี Java โดยไม่มีซอฟต์แวร์การสร้างแบบจำลอง 3D ใดๆ" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง GLB เป็น PDF โดยใช้ Java" %}}

 เพื่อแสดง GLB เป็น PDF เราจะใช้
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API ซึ่งเป็นแพลตฟอร์มการแปลง API for Java ที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 และติดตั้งภายในโปรเจ็กต์ที่ใช้ Maven โดยเพิ่มการกำหนดค่าต่อไปนี้ใน pom.xml

{{% blocks/products/pf/agp/code-block title="ที่เก็บ" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="การพึ่งพา" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-3d</artifactId>
<version>version of aspose-3d API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง GLB เป็น PDF ผ่าน Java" %}}

{{% blocks/products/pf/agp/text %}}

 โปรแกรมเมอร์ Java สามารถแปลงไฟล์ GLB เป็น PDF ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ GLB ผ่านตัวสร้างของ Scene class1. เรียกเมธอด Scene.save ด้วยรูปแบบของ PDF1. ตรวจสอบไฟล์ผลลัพธ์ PDF ที่เส้นทางที่ระบุ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ด Conversion Java ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป- รับเวอร์ชันล่าสุดของ Aspose.3D for Java โดยตรงจาก Maven
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="GLB ถึง PDF Java รหัสแหล่งที่มาของการแปลง" offSpacer="" %}}

```cs
// โหลดซอร์สไบนารี GLTF file
Scene scene = new Scene("sourceFile.glb");
// แปลง 3D ฉากเป็นไฟล์ใน 3D PDF รูปแบบ
scene.save("output.pdf", FileFormat.PDF)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="GLB ถึง PDF การสาธิตการแปลงสด" sectionDescription="[แปลง GLB เป็น PDF](https://products.aspose.app/3d/conversion/glb-to-pdf) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ GLB ของคุณ ไฟล์จะถูกแปลงเป็น PDF ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D ไลบรารีการจัดการฉาก" %}}

 Aspose.3D เป็น CAD และ Gameware API ในการโหลด แก้ไข และแปลงไฟล์ 3D API เป็นแบบสแตนด์อโลนและไม่จำเป็นต้องมี 3D ซอฟต์แวร์สร้างแบบจำลองหรือเรนเดอร์ใดๆ สามารถใช้ API สำหรับ USD, Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX และรูปแบบอื่นๆ 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}

GLB คือการแสดงรูปแบบไฟล์ไบนารีของโมเดล 3D ที่บันทึกในรูปแบบการส่ง GL (glTF) ข้อมูลเกี่ยวกับโมเดล 3D เช่น ลำดับชั้นของโหนด กล้อง วัสดุ แอนิเมชั่น และเมช ในรูปแบบไบนารี รูปแบบไบนารีนี้เก็บสินทรัพย์ glTF (JSON, .bin และรูปภาพ) ไว้ใน Blob แบบไบนารี นอกจากนี้ยังช่วยหลีกเลี่ยงปัญหาการเพิ่มขนาดไฟล์ซึ่งเกิดขึ้นในกรณีของ glTF รูปแบบไฟล์ GLB ส่งผลให้ขนาดไฟล์เล็กกะทัดรัด โหลดเร็ว แสดงฉาก 3D สมบูรณ์ และขยายเพื่อการพัฒนาต่อไป รูปแบบนี้ใช้ model/gltf-binary เป็นประเภท MIME

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/3d/pdf/" >}}

Portable Document Format (PDF) เป็นเอกสารประเภทหนึ่งที่ Adobe สร้างขึ้นในปี 1990 จุดประสงค์ของรูปแบบไฟล์นี้คือเพื่อแนะนำมาตรฐานสำหรับการนำเสนอเอกสารและเอกสารอ้างอิงอื่นๆ ในรูปแบบที่ไม่ขึ้นอยู่กับแอพพลิเคชั่นซอฟต์แวร์ ฮาร์ดแวร์ และระบบปฏิบัติการ PDF ไฟล์สามารถเปิดได้ใน Adobe Acrobat Reader/Writer และในเบราว์เซอร์สมัยใหม่ส่วนใหญ่ เช่น Chrome, Safari, Firefox ผ่านส่วนขยาย/ปลั๊กอิน ชุดซอฟต์แวร์ที่มีจำหน่ายในท้องตลาดส่วนใหญ่ยังมีการแปลงเอกสารเป็นรูปแบบไฟล์ PDF โดยไม่ต้องใช้ส่วนประกอบซอฟต์แวร์เพิ่มเติม


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง GLB เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-gltf/" name="GLB ถึง GLTF" description="ไฟล์รูปแบบการส่ง GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-pdf/" name="GLB ถึง PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-fbx/" name="GLB ถึง FBX" description="Autodesk FBX ไฟล์ Interchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-stl/" name="GLB ถึง STL" description="ไฟล์ Stereolithography" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-obj/" name="GLB ถึง OBJ" description="Wavefront 3D ไฟล์อ็อบเจ็กต์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-3ds/" name="GLB ถึง 3DS" description="3D ฉากสตูดิโอ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-dae/" name="GLB ถึง DAE" description="ไฟล์การแลกเปลี่ยนสินทรัพย์ดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-u3d/" name="GLB ถึง U3D" description="Universal 3D ไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-ply/" name="GLB ถึง PLY" description="รูปแบบไฟล์รูปหลายเหลี่ยม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-drc/" name="GLB ถึง DRC" description="Google Draco รูปแบบไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-rvm/" name="GLB ถึง RVM" description="อาวีว่า RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-jt/" name="GLB ถึง JT" description="JT เปิด CAD ไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-amf/" name="GLB ถึง AMF" description="ไฟล์การผลิตสารเติมแต่ง" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-html/" name="GLB ถึง HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-usd/" name="GLB ถึง USD" description="รูปแบบคำอธิบายฉากสากล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/glb-to-usdz/" name="GLB ถึง USDZ" description="คำอธิบายฉากสากล รูปแบบซิป" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}