﻿---
title: C# aracılığıyla GLB'i 3DS'ye dönüştürün 
weight: 530
url: /tr/net/conversion/glb-to-3ds/ 
description: GLB - 3DS C# dönüşümü için örnek kod. VB.NET, Asp.NET veya herhangi bir .NET tabanlı uygulama içinde toplu GLB dosyaları 3DS dönüştürme için API örnek kodunu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# aracılığıyla GLB\'i 3DS\'ye dönüştürün" h2="Herhangi bir 3D modelleme ve oluşturma yazılımı olmadan GLB\'i 3DS olarak oluşturun." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="3DS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanılarak GLB, 3DS\'ye Nasıl Dönüştürülür" %}}

 GLB'i 3DS'ye dönüştürmek için kullanacağız
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 C# platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir belge işleme ve dönüştürme API olan API. Açık
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 paket yöneticisi, ara
 Aspose.3D 
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Paket Yöneticisi Konsol Komutu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# aracılığıyla GLB\'i 3DS\'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programcıları, yalnızca birkaç kod satırıyla GLB dosyalarını kolayca yükleyebilir ve 3DS'ye dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. GLB dosyasını Scene sınıfının yapıcısı aracılığıyla yükleyin1. 3DS biçimiyle Scene.Save yöntemini çağırın.1. Belirtilen yolda ortaya çıkan 3DS dosyasını kontrol edin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 .NET dönüştürme kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono ile uyumlu bir işletim sistemi.- Microsoft Visual Studio gibi geliştirme ortamı.- Projenizde başvurulan Aspose.3D for .NET DLL.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod, GLB - 3DS C# Dönüşümünü gösterir" offSpacer="" %}}

```cs
// Kaynak Binary GLTF dosyasını yükleyin
Scene scene = new Scene("sourceFile.glb");
// 3D sahnesini Gizli 3DS biçiminde dosyaya dönüştürün
scene.Save("output.3ds", FileFormat.Discreet3DS)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="GLB\'i 3DS\'e Dönüştürmek için Ücretsiz Uygulama" sectionDescription="için canlı demolarımızı kontrol edin [GLB - 3DS dönüşüm](https://products.aspose.app/3d/conversion/glb-to-3ds) aşağıdaki faydaları ile." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Herhangi bir şey indirmenize veya kurmanıza gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece GLB dosyanızı yükleyin ve \"Dönüştür\" düğmesine basın." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Elde edilen 3DS dosyasının indirme bağlantısını anında alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D dosyalarını herhangi bir modelleme ve işleme yazılımı olmadan işlemek için bir 3D Dosya İşleme Kitaplığı. 3D API, Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB'i destekler, PLY, DirectX, Google Draco dosya biçimleri ve daha fazlası. Geliştiriciler, 3D belge biçimlerinin özünü kolayca oluşturabilir, okuyabilir, dönüştürebilir, değiştirebilir ve kontrol edebilir.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}
GLB, GL İletim Formatında (glTF) kaydedilen 3D modellerinin ikili dosya formatı temsilidir. Düğüm hiyerarşisi, kameralar, malzemeler, animasyonlar ve ağlar gibi 3D modelleri hakkında ikili biçimde bilgiler. Bu ikili biçim, glTF varlığını (JSON, .bin ve resimler) ikili bir blob içinde saklar. Ayrıca glTF durumunda meydana gelen dosya boyutunda artış sorununu da önler. GLB dosya biçimi, kompakt dosya boyutları, hızlı yükleme, eksiksiz 3D sahne gösterimi ve daha fazla geliştirme için genişletilebilirlik sağlar. Biçim, MIME türü olarak model/gltf-binary kullanır.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3ds" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
.3ds uzantılı bir dosya, Autodesk 3D Studio tarafından kullanılan 3D Sudio (DOS) ağ dosyası biçimini temsil eder. Autodesk 3D Studio, 1990'lardan beri 3D dosya formatı pazarındadır ve şimdi 3D modelleme, animasyon ve işleme ile çalışmak için 3D Studio MAX'a dönüşmüştür. Bir 3DS dosyası, sahnelerin ve görüntülerin 3D temsili için veriler içerir ve 3D veri içe ve dışa aktarma için popüler dosya biçimlerinden biridir. Bir sahneyi oluşturmak için tepe noktaları ve çokgenler oluşturmak için kamera konumları, Kafes verileri, aydınlatma bilgileri, görünüm alanı yapılandırmaları, düzleştirme grubu verileri, bitmap referansları ve öznitelikler gibi bilgileri dikkate alır.
        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca, GLB\'i aşağıda listelenen birkaç dosya biçimi de dahil olmak üzere birçok başka dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-gltf/" name="GLB - GLTF" description="GL İletim Format Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-pdf/" name="GLB - PDF" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-fbx/" name="GLB - FBX" description="Autodesk FBX Değişim Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-stl/" name="GLB - STL" description="Stereolitografi Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-obj/" name="GLB - OBJ" description="Wavefront 3D Nesne Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-3ds/" name="GLB - 3DS" description="3D Stüdyo Sahnesi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-dae/" name="GLB - DAE" description="Dijital Varlık Değişim Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-u3d/" name="GLB - U3D" description="Universal 3D Dosya" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-ply/" name="GLB - PLY" description="Çokgen Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-drc/" name="GLB - DRC" description="Google Draco Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-rvm/" name="GLB - RVM" description="AVVA RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-jt/" name="GLB - JT" description="JT CAD Dosyasını Aç" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-amf/" name="GLB - AMF" description="Eklemeli İmalat Dosyası" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-html/" name="GLB - HTML" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-usd/" name="GLB - USD" description="Evrensel Sahne Tanımlama Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/glb-to-usdz/" name="GLB - USDZ" description="Evrensel Sahne Açıklaması Sıkıştırılmış Format" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}