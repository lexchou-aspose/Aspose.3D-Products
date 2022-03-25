﻿---
title: JT 'i C# ile PDF 'ye dönüştürün 
weight: 2910
url: /tr/net/conversion/jt-to-pdf/ 
description: JT ila PDF C# dönüşümü için örnek kod. .NET, Asp.NET veya herhangi bir .NET tabanlı uygulamada PDF dönüşümüne kadar toplu JT dosyaları için API örnek kodu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="JT \'i C# ile PDF \'ye dönüştürün" h2="JT, herhangi bir 3D modelleme ve oluşturma yazılımı olmadan PDF olarak kullanın." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanarak JT \'i PDF \'e Nasıl Dönüştürebilirsiniz?" %}}

 JT 'i PDF 'ye dönüştürmek için kullanacağız
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, C# platformu için özellik açısından zengin, güçlü ve kullanımı kolay bir belge manipülasyonu ve dönüşümü API. Açık
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Paket yöneticisi, arama için
 Aspose.3D 
 Ve yükleyin. Paket Yöneticisi Konsolu'ndan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Paket Yöneticisi Konsolu Komutanlığı" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# üzerinden JT ile PDF \'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programcılar, JT dosyalarını sadece birkaç satır kodla PDF 'ye kolayca yükleyebilir ve dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. Scene sınıfının kurucusu aracılığıyla JT dosyasını yükle1. PdfSaveOptions örneğini oluşturma1. Gelişmiş dönüşüm için PDF özel özellikler ayarlayın1. Sahneyi arayın. Kaydet yöntemi1. Çıkış yolunu PDF dosya uzantısı ve PdfSaveOptions nesnesi ile geçin1. Belirtilen yolda ortaya çıkan PDF dosyasını kontrol edin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Sistem Gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 .NET dönüştürme kodunu çalıştırmadan önce, aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono ile uyumlu bir işletim sistemi.- Microsoft Visual Studio gibi geliştirme ortamı.- Aspose.3D for .NET DLL projenizde referans alınmıştır.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod JT ila PDF C# Dönüşümü gösterir" offSpacer="" %}}

```cs
// Bir sahne nesnesine JT yükleyin 
var document = new Aspose.ThreeD.Scene("template.jt");
// PdfSaveOptions örneğini oluşturun 
var options = new Aspose.ThreeD.Formats.PdfSaveOptions();
// JT 'i PDF olarak kaydedin 
document.Save("output.pdf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="JT \'i PDF \'e Dönüştürmek için Ücretsiz Uygulama" sectionDescription="Canlı demolarımızı kontrol edin [JT ila PDF dönüşüm](https://products.aspose.app/3d/conversion/jt-to-pdf) Aşağıdaki faydaları ile." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Hiçbir şey indirmeye veya kurmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece JT dosyanızı yükleyin ve \"Dönüştür\" düğmesine basın." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ortaya çıkan PDF dosyası için indirme bağlantısını anında alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D Dosya İşleme Kitaplığı, herhangi bir modelleme ve oluşturma yazılımı olmadan 3D dosyayı işlemek için. 3D API, Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, İkili), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco dosya formatları ve daha fazlası. Geliştiriciler, 3D belge formatlarının maddesini kolayca oluşturabilir, okuyabilir, dönüştürebilir, değiştirebilir ve kontrol edebilir.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JT" readMoreLink="https://docs.fileformat.com/3d/jt/" >}}
JT (Jupiter Tessellation), Siemens PLM Software tarafından geliştirilen verimli, endüstri odaklı ve esnek bir ISO standartlaştırılmış 3D veri formatıdır. Havacılık, otomotiv endüstrisi ve Ağır Ekipmanın mekanik CAD alanları, en önde gelen 3D görselleştirme formatı olarak JT 'yi kullanır. JT formatı, CAD özgü öznitelikleri ve düğümleri destekleyen bir sahne grafiğidir. Faset verilerini (üçgenler) depolamak için gelişmiş sıkıştırma teknikleri kullanılır. Bu format, görsel öznitelikleri, ürün ve üretim bilgilerini (PMI) ve Meta verileri destekleyecek şekilde yapılandırılmıştır. Eşzamansız içerik akışı için iyi bir destek var. Ağır mekanik endüstrisinde profesyoneller, karmaşık malların geometrisini incelemek için CAD çözümlerinde ve ürün yaşam döngüsü yönetimi (PLM) yazılım programlarında JT dosyasını kullanırlar.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="pdf" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Taşınabilir Belge Biçimi (PDF), 1990'larda Adobe tarafından oluşturulan bir belge türüdür. Bu dosya formatının amacı, belgelerin ve diğer referans materyallerin uygulama yazılımı, donanım ve İşletim Sisteminden bağımsız bir formatta gösterimi için bir standart sunmaktır. PDF dosyaları Adobe Acrobat Reader/Writer'da ve Chrome, Safari, Firefox gibi çoğu modern tarayıcıda uzantılar/eklentiler aracılığıyla açılabilir. Piyasada bulunan yazılım paketlerinin çoğu, herhangi bir ek yazılım bileşeni gerekmeden belgelerinin PDF dosya biçimine dönüştürülmesini de sunar. Bu nedenle, PDF dosya formatı, metin, görüntüler, köprüler, form alanları, zengin medya, dijital imzalar, ekler, meta veriler, Geospatial özellikler ve içindeki 3D nesneler gibi bilgileri içerme özelliğine sahiptir. kaynak belge.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Diğer Desteklenen Dönüşümler" subTitle="Ayrıca JT \'i aşağıda listelenen birkaç dosya da dahil olmak üzere diğer birçok dosya formatına dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-3ds/" name="JT TO 3DS" description="3D Stüdyo DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-amf/" name="JT TO AMF" description="Katkı Üretim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-dae/" name="JT TO DAE" description="Dijital Varlık Değişimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-fbx/" name="JT TO FBX" description="3D Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-html/" name="JT TO HTML" description="Hiper Metin Biçimlendirme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-obj/" name="JT TO OBJ" description="3D Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-ply/" name="JT TO PLY" description="Çokgen Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-rvm/" name="JT TO RVM" description="AVEVA Bitki Tasarım Modeli" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-stl/" name="JT TO STL" description="Değiştirilebilir 3D Yüzey Geometrisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-u3d/" name="JT TO U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}