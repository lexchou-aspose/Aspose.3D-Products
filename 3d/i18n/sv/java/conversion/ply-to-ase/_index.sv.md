﻿---
title: Konvertera PLY till ASE via Java 
weight: 890
url: /sv/java/conversion/ply-to-ase/ 
description: Prov Java konverteringskod för PLY-format till ASE-fil. Använd den här exempelkoden för att konvertera PLY till ASE inom någon webb- eller skrivbordsbaserad program Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera PLY till ASE via Java" h2="PLY till ASE konvertering med Java bibliotek utan någon 3D modelleringsprogram." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="ASE" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PLY" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Hur man konverterar PLY till ASE använder Java" %}}

 För att visa PLY till ASE, använder vi oss av.
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API som är en funktionsrika, kraftfull och lättanvänd konverteringsplattform API for Java. Du kan ladda ner den senaste versionen direkt från
 [Maven Ordförande](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 Och installera det i ditt Maven-baserade projekt genom att lägga till följande konfigurationer till pom.xml.

{{% blocks/products/pf/agp/code-block title="Arkiv" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Beroendet" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera PLY till ASE via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programmerare kan enkelt konvertera PLY filen till ASE på bara några få kodrader.

{{% /blocks/products/pf/agp/text %}}

1. Ladda PLY- filen via konstruktören i scenens klass1. Skapa en instans av AseSaveOptions1. Ange ASE specifika egenskaper för avancerad konvertering1. Ring Scene.save- metoden1. Passera utdata sökvägen med ASE filändelsen & objekt AseSaveOptions.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör Java konverteringskoden, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Applikationer och skrivbordsprogram.- Hämta senaste version av Aspose.3D for Java direkt från Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PLY till ASE Java Konverteringskältkod" offSpacer="" %}}

```cs
// Ladda PLY i ett objekt i Scene 
Scene document = new Scene("template.ply");
// Skapa en instans av AseSaveOptions 
AseSaveOptions options = new AseSaveOptions();
// Spara PLY som en ASE 
document.save("output.ase", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PLY till ASE Konvertering levande demos" sectionDescription="[Konvertera PLY till ASE](https://products.aspose.app/3d/conversion/ply-to-ase) Just nu genom att besöka vår Live Demos hemsida.The live demo har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Bara ladda upp din PLY-fil, den kommer att konverteras omedelbart till ASE." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer att få nedladdningslänken." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Scenmanipulationsbiblioteket" %}}

 Aspose.3D är en CAD och spelprogram API för att ladda, ändra och konvertera 3D filer. API är en fristående och kräver ingen 3D modellering eller rendering programvara. Man kan enkelt använda API för Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, binär), Collada, glTF, PLY, GLB, DirectX och fler format. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}

PLY, Polygon Filformat, representerar 3D filformat som lagrar grafiska objekt som beskrivs som en samling av polygoner. Syftet med detta filformat var att upprätta en enkel och enkel filtyp som är tillräckligt generellt för att vara användbar för ett brett sortiment. av modeller. PLY filformat kommer som ASCII samt binärt format för kompakt lagring och för snabbt sparande och lastning. Filformatet används av olika program som ger stöd för 3D filer läsning.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}

En ASE-fil är en 2D-animation eller grafik som innehåller lager, ramar, paletter, taggar och inställningar.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra stödda omvandlinger" subTitle="Du kan också konvertera PLY till många andra filformat, inklusive få listade nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-3ds/" name="PLY till 3DS" description="3D Studio DOS- mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-amf/" name="PLY till AMF" description="Tillverkningsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-dae/" name="PLY till DAE" description="Utbyte av digital tillgångar" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-fbx/" name="PLY till FBX" description="3D Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-gltf/" name="PLY till GLTF" description="GL- överföringsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-html/" name="PLY till HTML" description="Språk" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-obj/" name="PLY till OBJ" description="3D Filformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-rvm/" name="PLY till RVM" description="AVEVA Plant Design Modell" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-stl/" name="PLY till STL" description="Utbytbar 3D ytgeometri." >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-u3d/" name="PLY till U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}