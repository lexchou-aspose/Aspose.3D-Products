﻿---
title: Convert DRC to PDF via C# 
url: /cs/net/conversion/drc-to-pdf/ 
description: Vzorový kód pro konverzaci DRC na PDF C#. Použijte API příklad kódu pro dávku DRC souborů na PDF konverzaci v rámci vb .NET, asp .NET nebo kterékoli aplikace založené na .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convert DRC to PDF via C#" h2="Render DRC as PDF without any 3D modeling and rendering software." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak převést DRC na PDF pomocí C#" %}}

 Pro převádění DRC na PDF použijeme
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, který je bohatý na funkce, výkonný a snadno použitelné manipulace a konverzace dokumentů API pro platformu C#. Otevřít
 [Nuget](https://www.nuget.org/packages/aspose.3d) 
 Správce balíčků, hledat
 Aspose.3D 
 A nainstalovat. Můžete použít také následující příkaz z konzoly správce balíků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzoly správce balíků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro převod DRC na PDF prostřednictvím C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programátoři mohou snadno načíst a převést DRC soubory do PDF v několika řadách kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načíst soubor DRC prostřednictvím konstruktora třídy scény1. Vytvořit instance of amfsaveoptions1. Nastavit specifické vlastnosti PDF pro pokročilou konverzii1. Volejte scénu. uložit metodu1. Přejít výstupní cestu s PDF příponou souboru a objektem pdfsaveoptions1. Zkontrolovat výsledný soubor PDF při zadané cestě
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním kódu .NET se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft windows nebo kompatibilní os s .NET framework, .NET core, Mono.- Vývojové prostředí jako microsoft visual studio.- Aspose.3D for .NET dll odkazovaný ve vašem projektu.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tento vzorový kód ukazuje konverzaci DRC na PDF C#" offSpacer="" %}}

```cs
// Načíst DRC v objektu scény 
var document = new Aspose.ThreeD.Scene("template.drc");
// Vytvořit instanci pdfsaveoptions 
var options = new Aspose.ThreeD.Formats.PdfSaveOptions();
// Uložit DRC jako PDF 
document.Save("output.pdf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Free app to convert DRC to PDF" sectionDescription="Check our live demos for [Konverzace DRC na PDF](https://products.aspose.app/3d/conversion/drc-to-pdf) S následujícími přínosy." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba nic stáhnout nebo instalovat." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba napsat žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DRC file and hit the \"convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will immediately get the download link for resultant PDF file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Knihovna zpracování souborů 3D pro manipulaci souborů 3D bez modelování a vykreslování softwaru. 3D API podporuje Discreet3DS, WavefrontOBJ, FBX (ascii, binární), STL (ascii, binární), Universal3D, Collada, glTF, GLB, PLY, directx, Google Draco formáty souborů a další. Vývojáři mohou snadno vytvořit, číst, převést, upravit a ovládat obsah formátů 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
Spis s. Drc extension je komprimovaný formát 3D, vytvořený s knihovnou Google Draco. Google nabízí Draco jako knihovnu s otevřeným zdrojem pro komprimaci a dekomprimaci 3D geometrických sítí a bodových mračen a zlepšuje ukládání a přenos 3D grafiky. Kóduje vstupní data a ukládá je jako. Složka drc. Na přijímajícím konci číst API. Drc soubory a mohou je vydat jako PLY nebo OBJ soubory. Komprimovaný výstupní soubor umožňuje uživatelům rychleji stahovat aplikace a rychlé načtení 3D grafiky v prohlížečích.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="pdf" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable document format (PDF) is a type of document created by adobe back in 1990s. Účelem tohoto formátu souboru bylo zavést standard pro reprezentaci dokumentů a jiných referenčních materiálů ve formátu, který je nezávislý na aplikačním softwaru, hardwaru i operačním systému. PDF soubory lze otevřít v adobe acrobat reader/writer i ve většině moderních prohlížečů jako chrome, safari, firefox prostřednictvím rozšíření/zásuvných modulů. Většina komerčně dostupných softwarových balíčků také nabízí konverzaci jejich dokumentů do PDF formátu souboru bez požadavku jakékoli další softwarové složky. PDF formát souborů má plnou schopnost obsahovat informace jako text, obrázky, hypertextové odkazy, pole formulářů, bohaté média, digitální podpisy, přílohy, metadata, geospatial features and 3D objects in it that can become as part of source document.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}