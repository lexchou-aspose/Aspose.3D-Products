﻿---
title: Ubah PLY menjadi STL melalui Java 
weight: 800
url: /id/java/conversion/ply-to-stl/ 
description: Contoh Java kode konversi untuk format PLY ke file STL. Gunakan kode contoh ini untuk mengonversi PLY ke STL dalam aplikasi berbasis Web atau Desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Ubah PLY menjadi STL melalui Java" h2="Konversi PLY ke STL menggunakan pustaka Java tanpa perangkat lunak pemodelan 3D apa pun." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PLY" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Cara Mengonversi PLY ke STL Menggunakan Java" %}}

 Untuk merender PLY menjadi STL, kami akan menggunakan
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API yang merupakan platform API for Java konversi yang kaya fitur, canggih, dan mudah digunakan. Anda dapat mengunduh versi terbarunya langsung dari
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 dan instal dalam proyek berbasis Maven Anda dengan menambahkan konfigurasi berikut ke pom.xml.

{{% blocks/products/pf/agp/code-block title="Gudang" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repositori.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Ketergantungan" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Langkah-langkah untuk Mengonversi PLY ke STL melalui Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java pemrogram dapat dengan mudah mengonversi berkas PLY menjadi STL hanya dalam beberapa baris kode.

{{% /blocks/products/pf/agp/text %}}

1. Muat file PLY melalui konstruktor kelas Scene1. Buat instance StlSaveOptions1. Tetapkan STL properti khusus untuk konversi lanjutan1. Metode panggilan Scene.save1. Lewati jalur keluaran dengan STL ekstensi file & objek StlSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan sistem" %}}

{{% blocks/products/pf/agp/text %}}

 Sebelum menjalankan Java kode konversi, pastikan Anda memiliki prasyarat berikut.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows atau OS yang kompatibel dengan Java Runtime Environment untuk Aplikasi JSP/JSF dan Aplikasi Desktop.- Dapatkan versi terbaru Aspose.3D for Java langsung dari Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PLY ke STL Java Kode Sumber Konversi" offSpacer="" %}}

```cs
// memuat PLY dalam objek Scene 
Scene document = new Scene("template.ply");
// buat instance StlSaveOptions 
StlSaveOptions options = new StlSaveOptions();
// simpan PLY sebagai STL 
document.save("output.stl", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="PLY ke STL Demo Konversi Langsung" sectionDescription="[Ubah PLY menjadi STL](https://products.aspose.app/3d/conversion/ply-to-stl) sekarang dengan mengunjungi situs web Demo Langsung kami. Demo langsung memiliki manfaat sebagai berikut" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Tidak perlu mengunduh Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Tidak perlu menulis kode apa pun." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Cukup unggah file PLY Anda, itu akan langsung dikonversi menjadi STL." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Anda akan mendapatkan tautan unduhan." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Pustaka Manipulasi Adegan" %}}

 Aspose.3D adalah CAD dan Gameware API untuk memuat, memodifikasi, dan mengonversi file 3D. API berdiri sendiri dan tidak memerlukan perangkat lunak pemodelan atau rendering 3D apa pun. Seseorang dapat dengan mudah menggunakan API untuk Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX, dan format lainnya. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}

PLY, Format Berkas Poligon, mewakili 3D format berkas yang menyimpan objek grafis yang dijelaskan sebagai kumpulan poligon. Tujuan dari format file ini adalah untuk membuat tipe file yang sederhana dan mudah yang cukup umum untuk berguna untuk berbagai model. Format file PLY hadir sebagai ASCII serta format Biner untuk penyimpanan ringkas dan untuk penyimpanan dan pemuatan cepat. Format file digunakan oleh berbagai aplikasi yang menyediakan dukungan untuk 3D pembacaan file.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}

STL, singkatan dari stereolithrography, adalah format file yang dapat dipertukarkan yang mewakili geometri permukaan 3 dimensi. Format file menemukan penggunaannya di beberapa bidang seperti pembuatan prototipe cepat, pencetakan 3D, dan manufaktur berbantuan komputer. Ini mewakili permukaan sebagai serangkaian segitiga kecil, yang dikenal sebagai segi, di mana setiap segi dijelaskan oleh arah tegak lurus dan tiga titik yang mewakili simpul segitiga. Data yang dihasilkan digunakan oleh aplikasi untuk menentukan penampang bentuk 3D yang akan dibangun oleh fabber. Tidak ada informasi yang tersedia dalam format file STL untuk representasi warna, tekstur, atau atribut model CAD umum lainnya.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Konversi yang Didukung Lainnya" subTitle="Anda juga dapat mengonversi PLY ke banyak format file lain termasuk beberapa yang tercantum di bawah ini." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-3ds/" name="PLY KE 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-amf/" name="PLY KE AMF" description="Format Manufaktur Aditif" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-ase/" name="PLY KE ASE" description="File Animasi 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-dae/" name="PLY KE DAE" description="Pertukaran Aset Digital" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-fbx/" name="PLY KE FBX" description="3D Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-gltf/" name="PLY KE GLTF" description="Format Transmisi GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-html/" name="PLY KE HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-obj/" name="PLY KE OBJ" description="3D Format Berkas" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-rvm/" name="PLY KE RVM" description="Model Desain Tanaman AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-u3d/" name="PLY KE U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}