﻿---
title: Convert STL to DRC via C# 
url: /cs/net/conversion/stl-to-drc/ 
description: Vzorový kód pro konverzaci STL na DRC C#. Použijte API příklad kódu pro dávku STL souborů na DRC konverzaci v rámci vb .NET, asp .NET nebo kterékoli aplikace založené na .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convert STL to DRC via C#" h2="Render STL as DRC without any 3D modeling and rendering software." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DRC" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="STL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak převést STL na DRC pomocí C#" %}}

 Pro převádění STL na DRC použijeme
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro převod STL na DRC prostřednictvím C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programátoři mohou snadno načíst a převést STL soubory do DRC v několika řadách kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načíst soubor STL prostřednictvím konstruktora třídy scény1. Vytvořit instance of amfsaveoptions1. Nastavit specifické vlastnosti DRC pro pokročilou konverzii1. Volejte scénu. uložit metodu1. Přejít výstupní cestu s DRC rozšířením souboru a objektem drcsaveoptions1. Zkontrolovat výsledný soubor DRC při zadané cestě
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním kódu .NET se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft windows nebo kompatibilní os s .NET framework, .NET core, Mono.- Vývojové prostředí jako microsoft visual studio.- Aspose.3D for .NET dll odkazovaný ve vašem projektu.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tento vzorový kód ukazuje konverzaci STL na DRC C#" offSpacer="" %}}

```cs
// Načíst STL v objektu scény 
var document = new Aspose.ThreeD.Scene("template.stl");
// Vytvořit instanci drcsaveoptions 
var options = new Aspose.ThreeD.Formats.DrcSaveOptions();
// Uložit STL jako DRC 
document.Save("output.drc", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Free app to convert STL to DRC" sectionDescription="Check our live demos for [Konverzace STL na DRC](https://products.aspose.app/3d/conversion/stl-to-drc) S následujícími přínosy." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba nic stáhnout nebo instalovat." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba napsat žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your STL file and hit the \"convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will immediately get the download link for resultant DRC file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Knihovna zpracování souborů 3D pro manipulaci souborů 3D bez modelování a vykreslování softwaru. 3D API podporuje Discreet3DS, WavefrontOBJ, FBX (ascii, binární), STL (ascii, binární), Universal3D, Collada, glTF, GLB, PLY, directx, Google Draco formáty souborů a další. Vývojáři mohou snadno vytvořit, číst, převést, upravit a ovládat obsah formátů 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL, zkratka pro stereolitrografii, je výměnný formát souboru, který reprezentuje trojrozměrnou geometrii povrchu. Formát souboru najde jeho použití v několika oblastech, jako je rychlé prototyping, 3D tisk a počítačová výroba. Představuje plochu jako řadu malých trojúhelníků, známých jako facety, kde je každý facet popsán kolmým směrem a třemi body představujícími vrcholy trojúhelníku. Výsledná data jsou používána aplikacemi k určení průřezu tvaru 3D, který má fabber sestavit. Není k dispozici žádné informace ve formátu STL pro zobrazení barev, textury nebo jiných běžných atributů modelu CAD.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="drc" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
Spis s. Drc extension je komprimovaný formát 3D, vytvořený s knihovnou Google Draco. Google nabízí Draco jako knihovnu s otevřeným zdrojem pro komprimaci a dekomprimaci 3D geometrických sítí a bodových mračen a zlepšuje ukládání a přenos 3D grafiky. Kóduje vstupní data a ukládá je jako. Složka drc. Na přijímajícím konci číst API. Drc soubory a mohou je vydat jako PLY nebo OBJ soubory. Komprimovaný výstupní soubor umožňuje uživatelům rychleji stahovat aplikace a rychlé načtení 3D grafiky v prohlížečích.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované převody" subTitle="Můžete také převést STL do mnoha jiných formátů souborů, včetně několika uvedených níže." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-3ds/" name="STL až 3DS" description="3D studio dos mesh" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-amf/" name="STL až AMF" description="Aditivní formát výroby" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-dae/" name="STL až DAE" description="Výměna digitálních aktiv" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-fbx/" name="STL až FBX" description="Formát 3D" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-html/" name="STL až HTML" description="Jazyk označování hypertextů" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-obj/" name="STL až OBJ" description="3D formát souboru" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-pdf/" name="STL až PDF" description="Formát přenosného dokumentu" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-ply/" name="STL až PLY" description="Formát souboru polygon" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-rvm/" name="STL až RVM" description="Aveva plant design model" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-u3d/" name="STL až U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}