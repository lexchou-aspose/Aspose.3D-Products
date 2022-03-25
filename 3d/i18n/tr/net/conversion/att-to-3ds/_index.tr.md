﻿---
title: ATT 'i C# ile 3DS 'ye dönüştürün 
url: /tr/net/conversion/att-to-3ds/ 
description: ATT ila 3DS C# dönüşümü için örnek kod. .NET, Asp.NET veya herhangi bir .NET tabanlı uygulamada 3DS dönüşümüne kadar toplu ATT dosyaları için API örnek kodu kullanın.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="ATT \'i C# ile 3DS \'ye dönüştürün" h2="ATT, herhangi bir 3D modelleme ve oluşturma yazılımı olmadan 3DS olarak kullanın." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="3DS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ATT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanarak ATT \'i 3DS \'e Nasıl Dönüştürebilirsiniz?" %}}

 ATT 'i 3DS 'ye dönüştürmek için kullanacağız
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

{{% blocks/products/pf/agp/feature-section-col title="C# üzerinden ATT ile 3DS \'ye Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programcılar, ATT dosyalarını sadece birkaç satır kodla 3DS 'ye kolayca yükleyebilir ve dönüştürebilir.

{{% /blocks/products/pf/agp/text %}}

1. Scene sınıfının kurucusu aracılığıyla ATT dosyasını yükle1. AmfSaveOptions örneğini oluşturun1. Gelişmiş dönüşüm için 3DS özel özellikler ayarlayın1. Sahneyi arayın. Kaydet yöntemi1. Çıktı yolunu 3DS dosya uzantısı ve Discreet3dsSaveOptions nesnesi ile geçin1. Belirtilen yolda ortaya çıkan 3DS dosyasını kontrol edin
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Sistem Gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 .NET dönüştürme kodunu çalıştırmadan önce, aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono ile uyumlu bir işletim sistemi.- Microsoft Visual Studio gibi geliştirme ortamı.- Aspose.3D for .NET DLL projenizde referans alınmıştır.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu örnek kod ATT ila 3DS C# Dönüşümü gösterir" offSpacer="" %}}

```cs
// Bir sahne nesnesine ATT yükleyin 
var document = new Aspose.ThreeD.Scene("template.att");
// Discreet3dsSaveOptions örneğini oluşturun 
var options = new Aspose.ThreeD.Formats.Discreet3dsSaveOptions();
// ATT 'i 3DS olarak kaydedin 
document.Save("output.3ds", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="ATT \'i 3DS \'e Dönüştürmek için Ücretsiz Uygulama" sectionDescription="Canlı demolarımızı kontrol edin [ATT ila 3DS dönüşüm](https://products.aspose.app/3d/conversion/att-to-3ds) Aşağıdaki faydaları ile." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Hiçbir şey indirmeye veya kurmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Herhangi bir kod yazmaya gerek yok." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece ATT dosyanızı yükleyin ve \"Dönüştür\" düğmesine basın." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Ortaya çıkan 3DS dosyası için indirme bağlantısını anında alacaksınız." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D Dosya İşleme Kitaplığı, herhangi bir modelleme ve oluşturma yazılımı olmadan 3D dosyayı işlemek için. 3D API, Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, İkili), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco dosya formatları ve daha fazlası. Geliştiriciler, 3D belge formatlarının maddesini kolayca oluşturabilir, okuyabilir, dönüştürebilir, değiştirebilir ve kontrol edebilir.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ATT" readMoreLink="/{{att_url}}" >}}
{{att}}

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3ds" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
3DS uzantılı bir dosya, Autodesk 3D Studio tarafından kullanılan 3D Studio (DOS) örgü dosya biçimini temsil eder. Autodesk 3D Studio, 1990'lardan beri 3D dosya formatı pazarındadır ve şimdi 3D modelleme, animasyon ve işleme ile çalışmak için 3D Studio MAX'a dönüşmüştür. Bir 3DS dosyası, sahnelerin ve görüntülerin 3D gösterimi için veri içerir ve 3D veri içe aktarma ve dışa aktarma için popüler dosya biçimlerinden biridir. Bir sahneyi oluşturmak için köşeler ve çokgenler oluşturmak için kamera konumları, Ağ verileri, aydınlatma bilgileri, görüntüleme portu yapılandırmaları, düzeltici grup verileri, bitmap referansları ve nitelikler gibi bilgileri dikkate alır.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}