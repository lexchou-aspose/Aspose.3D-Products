﻿---
title: C# aracılığıyla X'i FBX'e dönüştürün 
weight: 1920
url: /tr/net/conversion/x-to-fbx/ 
description: X'ten FBX C#'e dönüşüm için örnek kod. VB.NET, Asp.NET veya herhangi bir .NET tabanlı uygulama içinde toplu X dosyalarını FBX dönüştürme için API örnek kodunu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# aracılığıyla X\'i FBX\'e dönüştürün" h2="Herhangi bir 3D modelleme ve işleme yazılımı olmadan X\'i FBX olarak işleyin." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="X" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanılarak X\'i FBX\'e Dönüştürme" %}}

 X'i FBX'e dönüştürmek için kullanacağız
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

{{% blocks/products/pf/agp/feature-section-col title="C# aracılığıyla X\'i FBX\'e Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programcıları, yalnızca birkaç kod satırıyla X dosyalarını kolayca yükleyebilir ve FBX dosyasına dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. Scene sınıfının yapıcısı aracılığıyla X dosyasını yükleyin1. Bir FbxSaveOptions örneği oluşturun1. Gelişmiş dönüştürme için FBX belirli özelliği ayarlayın1. Scene.Save yöntemini çağırın1. FBX dosya uzantısı ve FbxSaveOptions nesnesi ile çıktı yolunu iletin1. Belirtilen yolda ortaya çıkan FBX dosyasını kontrol edin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 .NET dönüştürme kodunu çalıştırmadan önce aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono ile uyumlu bir işletim sistemi.- Microsoft Visual Studio gibi geliştirme ortamı.- Projenizde başvurulan Aspose.3D for .NET DLL.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod, X - FBX C# Dönüşümünü gösterir" offSpacer="" %}}

```cs
// X'i Scene nesnesine yükleyin 
var document = new Aspose.ThreeD.Scene("template.x");
// bir FbxSaveOptions örneği oluşturun 
var options = new Aspose.ThreeD.Formats.FbxSaveOptions();
// X'i FBX olarak kaydet 
document.Save("output.fbx", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="X\'i FBX\'e Dönüştürmek için Ücretsiz Uygulama" sectionDescription="için canlı demolarımızı kontrol edin [X\'ten FBX\'e dönüşüm](https://products.aspose.app/3d/conversion/x-to-fbx) aşağıdaki faydaları ile." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Herhangi bir şey indirmenize veya kurmanıza gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece X dosyanızı yükleyin ve \"Dönüştür\" düğmesine basın." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Elde edilen FBX dosyasının indirme bağlantısını anında alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D dosyalarını herhangi bir modelleme ve işleme yazılımı olmadan işlemek için bir 3D Dosya İşleme Kitaplığı. 3D API, Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB'i destekler, PLY, DirectX, Google Draco dosya biçimleri ve daha fazlası. Geliştiriciler, 3D belge biçimlerinin özünü kolayca oluşturabilir, okuyabilir, dönüştürebilir, değiştirebilir ve kontrol edebilir.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="X" readMoreLink="https://docs.fileformat.com/3d/x/" >}}
X, oyunlarda 3D grafik oluşturma için DirectX teknolojisi tarafından kullanılan bir DirectX Model görüntü dosyasıdır. Dosya biçimi, ağlar, dokular, animasyonlar ve nesneler için 3D nesne yapılarını belirtir.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="fbx" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox, Kaydara tarafından MotionBuilder için geliştirilmiş, popüler bir 3D dosya biçimidir. 2006 yılında Autodesk Inc tarafından satın alındı ve şu anda birçok 3D aracı tarafından kullanılan ana 3D değişim biçimlerinden biri. FBX hem ikili hem de ASCII dosya biçiminde mevcuttur. Format, dijital içerik oluşturma uygulamaları arasında birlikte çalışabilirliği sağlamak için oluşturulmuştur. FBX dosya biçiminden/dosya biçimine dönüştürme için kullanılabilecek birçok araç vardır.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="Ayrıca, X\'i aşağıda listelenen birkaçı dahil olmak üzere birçok başka dosya biçimine dönüştürebilirsiniz." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-3ds/" name="X\'DEN 3DS\'E" description="3D Studio DOS Ağı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-amf/" name="X\'DEN AMF\'E" description="Eklemeli Üretim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-dae/" name="X\'DEN DAE\'E" description="Dijital Varlık Değişimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-html/" name="X\'DEN HTML\'E" description="Hiper Metin İşaretleme Dili" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-obj/" name="X\'DEN OBJ\'E" description="3D Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-pdf/" name="X\'DEN PDF\'E" description="Taşınabilir Döküman Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-ply/" name="X\'DEN PLY\'E" description="Çokgen Dosya Biçimi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-rvm/" name="X\'DEN RVM\'E" description="AVEVA Fabrika Tasarım Modeli" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-stl/" name="X\'DEN STL\'E" description="Değiştirilebilir 3D Yüzey Geometrisi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/x-to-u3d/" name="X\'DEN U3D\'E" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}