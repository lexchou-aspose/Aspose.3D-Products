﻿---
title: Convert DXF to HTML via Java 
weight: 3070
url: /cs/java/conversion/dxf-to-html/ 
description: Vzorek Java konverzní kód pro formát DXF do souboru HTML. Použijte tento příkladný kód k převedení DXF na HTML v rámci kterékoli aplikace založené na webu nebo ploše Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convert DXF to HTML via Java" h2="Konverzace DXF na HTML pomocí knihovny Java bez modelovacího softwaru 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Jak převést DXF na HTML pomocí Java" %}}

 K vykreslování DXF do HTML použijeme
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API, která je funkčně bohatá, výkonná a snadno použitelná platforma konverzace API for Java. Its latest version can download directly from
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 A nainstalujte ho do projektu založeného na maven přidáním následujících konfigurací do pom.xml.

{{% blocks/products/pf/agp/code-block title="Úložiště" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Závislost" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro převod DXF na HTML prostřednictvím Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programátoři mohou snadno převést soubor DXF na HTML v několika řádcích kódu.

{{% /blocks/products/pf/agp/text %}}

1. Načíst soubor DXF prostřednictvím konstruktora třídy scény1. Vytvořit instanci htmlsaveoptions1. Nastavit specifické vlastnosti HTML pro pokročilou konverzii1. Volání scény. uložit metodu1. Přejít výstupní cestu s HTML rozšířením souboru a objektem htmlsaveoptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Před spuštěním kódu Java se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft windows nebo kompatibilní operační systém s Java runtime prostředí pro aplikace a desktopové aplikace jsp/jsf.- Získejte poslední verzi Aspose.3D for Java přímo z maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DXF to HTML Java conversion source code" offSpacer="" %}}

```cs
// Načíst DXF v objektu scény 
Scene document = new Scene("template.dxf");
// Vytvořit instanci htmlsaveoptions 
Html5SaveOptions options = new Html5SaveOptions();
// Uložit DXF jako HTML 
document.save("output.html", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Konverzace live demonstrací DXF na HTML" sectionDescription="[Převést DXF na HTML](https://products.aspose.app/3d/conversion/dxf-to-html) Právě teď navštívit naše live demos webové stránky. live demo má následující výhody" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stáhnout Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba napsat žádný kód." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DXF file, it will be converted instantly to HTML." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D knihovna manipulace scény" %}}

 Aspose.3D je CAD a gameware API pro načtení, úpravu a převod souborů 3D. API je samostatný a nevyžaduje žádný 3D modelování nebo vykreslování softwaru. Lze snadno použít API pro Discreet3DS, WavefrontOBJ, STL (ascii, binární), Universal3D, FBX (ascii, binární), Collada, glTF, PLY, GLB, directx a další formáty. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}

DXF, formát výměny výkresů nebo formát výměny výkresů, je označená datová reprezentace souboru výkresu autocad. Každý prvek v souboru má předponu celé číslo, které se nazývá skupinový kód. Tento kód skupiny skutečně představuje prvek, který následuje, a označuje význam datového prvku pro daný typ objektu. DXF umožňuje zobrazit téměř všechny informace zadané uživatelem v souboru výkresu. DXF formát souboru byl vyvinut společností autodesk jako CAD formát datového souboru pro interoperabilitu dat mezi autocad a jinými aplikacemi. Data lze tedy importovat z jiných formátů do DXF do autocad podle specifikací interoperability ve formátu DXF.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (hyper text markup language) je rozšíření pro webové stránky vytvořené pro zobrazení v prohlížečích. HTML, známý jako jazyk webu, se vyvinul s požadavky na nové požadavky na informace, které mají být zobrazeny jako součást webových stránek. Nejnovější varianta je známá jako HTML 5, která poskytuje velkou flexibilitu pro práci s jazykem. HTML stránky jsou buď obdrženy ze serveru, kde jsou umístěny, nebo mohou být načteny i z místního systému. Každá stránka HTML se skládá z prvků HTML, jako jsou formuláře, text, obrázky, animace, odkazy atd. tyto prvky jsou reprezentovány značkami, jako jsou img, a, p a několik dalších, kde každá značka má začátek a konec. It can also embed applications written in scripting languages such as javascript and style sheets (css) for overall layout representation.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporované převody" subTitle="Můžete také převést DXF do mnoha jiných formátů souborů, včetně několika uvedených níže." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-3ds/" name="DXF až 3DS" description="3D studio dos mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-amf/" name="DXF až AMF" description="Aditivní formát výroby" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ase/" name="DXF až ASE" description="Soubor 2d animace" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-dae/" name="DXF až DAE" description="Výměna digitálních aktiv" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-fbx/" name="DXF až FBX" description="Formát 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-gltf/" name="DXF až GLTF" description="Formát přenosu gl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-obj/" name="DXF až OBJ" description="3D formát souboru" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ply/" name="DXF až PLY" description="Formát souboru polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-rvm/" name="DXF až RVM" description="Aveva plant design model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-stl/" name="DXF až STL" description="Zaměnitelná geometrie povrchu 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-u3d/" name="DXF až U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}