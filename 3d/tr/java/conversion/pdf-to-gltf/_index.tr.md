﻿---
title: Java aracılığıyla PDF'i GLTF'ye dönüştürün
weight: 530
url: /tr/java/conversion/pdf-to-gltf/ 
description: PDF biçimi için GLTF dosyasına örnek Java dönüştürme kodu. Herhangi bir Web veya Masaüstü Java tabanlı uygulamada PDF'ü GLTF'e dönüştürmek için bu örnek kodu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java aracılığıyla PDF\'i GLTF\'ye dönüştürün" h2="Herhangi bir 3D modelleme yazılımı olmadan Java kitaplığını kullanarak PDF - GLTF dönüştürme." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Java Kullanılarak PDF, GLTF\'ye Nasıl Dönüştürülür" %}}

 PDF'i GLTF olarak oluşturmak için kullanacağız
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 Zengin özelliklere sahip, güçlü ve kullanımı kolay bir dönüşüm API for Java platformu olan API. En son sürümünü doğrudan adresinden indirebilirsiniz.
 [Uzman](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 ve pom.xml dosyasına aşağıdaki konfigürasyonları ekleyerek Maven tabanlı projenize kurun.

{{% blocks/products/pf/agp/code-block title="depo" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Bağımlılık" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Java aracılığıyla PDF\'i GLTF\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Java programcıları, yalnızca birkaç satır kodla PDF dosyasını GLTF'ye kolayca dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. PDF dosyasını Scene sınıfının yapıcısı aracılığıyla yükleyin1. GLTF biçimiyle Scene.save yöntemini çağırın.1. Belirtilen yolda ortaya çıkan GLTF dosyasını kontrol edin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Java dönüştürme kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya JSP/JSF Uygulaması ve Masaüstü Uygulamaları için Java Runtime Environment ile uyumlu bir işletim sistemi.- Aspose.3D for Java'in en son sürümünü doğrudan Maven'den alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PDF - GLTF Java Dönüşüm Kaynak Kodu" offSpacer="" %}}

```cs
// Kaynak 3D PDF dosyasını yükleyin
Scene scene = new Scene("sourceFile.pdf");
// 3D sahnesini GLTF biçiminde dosyaya dönüştürün
scene.save("output.gltf", FileFormat.GLTF2)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="PDF - GLTF Dönüşüm Canlı Demoları" sectionDescription="[PDF\'i GLTF\'ye dönüştür](https://products.aspose.app/3d/conversion/pdf-to-gltf) Hemen şimdi Canlı Demolar web sitemizi ziyaret ederek. Canlı demo aşağıdaki avantajlara sahiptir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API dosyasını indirmenize gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece PDF dosyanızı yükleyin, anında GLTF dosyasına dönüştürülecektir." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" İndirme bağlantısını alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Sahne Manipülasyon Kitaplığı" %}}

 Aspose.3D, 3D dosyalarını yüklemek, değiştirmek ve dönüştürmek için kullanılan bir CAD ve Oyun Yazılımıdır API. API bağımsızdır ve herhangi bir 3D modelleme veya işleme yazılımı gerektirmez. USD, Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF için API kolayca kullanılabilir, PLY, GLB, DirectX ve diğer biçimler. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/3d/pdf/" >}}

Taşınabilir Belge Biçimi (PDF), Adobe tarafından 1990'larda oluşturulmuş bir belge türüdür. Bu dosya biçiminin amacı, belgelerin ve diğer başvuru malzemelerinin uygulama yazılımı, donanım ve İşletim Sisteminden bağımsız bir biçimde temsil edilmesi için bir standart getirmekti. PDF dosyaları, uzantılar/eklentiler aracılığıyla Adobe Acrobat Reader/Writer'da ve Chrome, Safari, Firefox gibi çoğu modern tarayıcıda açılabilir. Ticari olarak satılan yazılım paketlerinin çoğu, herhangi bir ek yazılım bileşenine gerek duymadan belgelerinin PDF dosya biçimine dönüştürülmesini de sağlar.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF (GL İletim Biçimi), 3D model bilgilerini JSON biçiminde depolayan bir 3D dosya biçimidir. JSON kullanımı, hem 3D varlıkların boyutunu hem de bu varlıkları paketinden çıkarmak ve kullanmak için gereken çalışma zamanı işlemlerini en aza indirir. Uygulamalar tarafından 3D sahnelerin ve modellerin verimli iletimi ve yüklenmesi için benimsenmiştir. glTF, Khronos Group 3D Formats Working Group tarafından geliştirilmiştir ve yaratıcıları tarafından 3D JPEG olarak da tanımlanır. Biçim, yazma iş akışlarını kolaylaştıran ve endüstri genelinde içeriğin birlikte çalışabilir şekilde kullanılmasını sağlayan 3D içerik araçları ve hizmetleri için genişletilebilir, ortak bir yayınlama biçimi tanımlar. glTF dosya biçiminin yaratılmasının ardındaki amaç, 3D içerik araçları ve hizmetleri için, yazma iş akışlarını kolaylaştıracak ve endüstri genelinde içeriğin birlikte çalışabilir kullanımına olanak sağlayacak genişletilebilir, ortak bir yayınlama biçimi tanımlamaktı. WebGL ve diğer API'leri kullanan uygulamalar tarafından çalışma zamanı işlemeyi en aza indirir.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca, PDF\'i aşağıda listelenen birkaç dosya biçimi de dahil olmak üzere birçok başka dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-gltf/" name="PDF - GLTF" description="GL İletim Format Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-glb/" name="PDF - GLB" description="İkili GL İletim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-fbx/" name="PDF - FBX" description="Autodesk FBX Değişim Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-stl/" name="PDF - STL" description="Stereolitografi Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-obj/" name="PDF - OBJ" description="Wavefront 3D Nesne Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-3ds/" name="PDF - 3DS" description="3D Stüdyo Sahnesi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-dae/" name="PDF - DAE" description="Dijital Varlık Değişim Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-u3d/" name="PDF - U3D" description="Universal 3D Dosya" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-ply/" name="PDF - PLY" description="Çokgen Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-drc/" name="PDF - DRC" description="Google Draco Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-rvm/" name="PDF - RVM" description="AVVA RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-jt/" name="PDF - JT" description="JT CAD Dosyasını Aç" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-amf/" name="PDF - AMF" description="Eklemeli İmalat Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-html/" name="PDF - HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-usd/" name="PDF - USD" description="Evrensel Sahne Tanımlama Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/pdf-to-usdz/" name="PDF - USDZ" description="Evrensel Sahne Açıklaması Sıkıştırılmış Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}