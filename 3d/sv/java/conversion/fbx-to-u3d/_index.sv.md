﻿---
title: Konvertera FBX till U3D via Java 
weight: 130
url: /sv/java/conversion/fbx-to-u3d/ 
description: Exempel på Java-konverteringskod för FBX-format till U3D-fil. Använd den här exempelkoden för att konvertera FBX till U3D i valfri webb- eller datorbaserad applikation Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera FBX till U3D via Java" h2="FBX till U3D omvandling med Java-biblioteket utan någon 3D-modelleringsprogramvara." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du FBX till U3D med Java" %}}

 För att rendera FBX till U3D använder vi
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API som är en funktionsrik, kraftfull och lättanvänd konverteringsplattform API for Java. Du kan ladda ner den senaste versionen direkt från
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 och installera det i ditt Maven-baserade projekt genom att lägga till följande konfigurationer till pom.xml.

{{% blocks/products/pf/agp/code-block title="Förvar" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Beroende" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera FBX till U3D via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-programmerare kan enkelt konvertera FBX-filen till U3D på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda FBX-filen via konstruktorn för Scene-klassen1. Skapa en instans av U3dSaveOptions1. Ställ in U3D specifika egenskaper för avancerad konvertering1. Ring Scene.save-metoden1. Skicka utdatasökvägen med U3D filtillägg och objekt för U3dSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör omvandlingskoden Java, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Application och Desktop Applications.- Hämta den senaste versionen av Aspose.3D for Java direkt från Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="FBX till U3D Java Omvandlingskällkod" offSpacer="" %}}

```cs
// ladda FBX i ett objekt av Scene 
Scene document = new Scene("template.fbx");
// skapa en instans av U3dSaveOptions 
U3dSaveOptions options = new U3dSaveOptions();
// spara FBX som en U3D 
document.save("output.u3d", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="FBX till U3D Live Demos för konvertering" sectionDescription="[Konvertera FBX till U3D](https://products.aspose.app/3d/conversion/fbx-to-u3d) just nu genom att besöka vår Live Demos-webbplats. Livedemon har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ned Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din FBX-fil, den konverteras omedelbart till U3D." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer att få nedladdningslänken." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Scenmanipulationsbibliotek" %}}

 Aspose.3D är ett CAD och spelprogram API för att ladda, ändra och konvertera 3D filer. API är en fristående och kräver ingen 3D-modellerings- eller renderingsprogramvara. Man kan enkelt använda API för Discreet3DS, WavefrontOBJ, STL (ASCII, binär), Universal3D, FBX (ASCII, binär), Collada, glTF, PLY, GLB, DirectX och fler format. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}

FBX, FilmBox, är ett populärt 3D-filformat som ursprungligen utvecklades av Kaydara för MotionBuilder. Det förvärvades av Autodesk Inc 2006 och är nu ett av de viktigaste 3D-utbytesformaten som används av många 3D-verktyg. FBX är tillgänglig i både binärt och ASCII-filformat. Formatet skapades för att tillhandahålla interoperabilitet mellan applikationer för skapande av digitalt innehåll. Det finns många tillgängliga verktyg för konvertering från/till filformatet FBX.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}

U3D (Universal 3D) är ett komprimerat filformat och datastruktur för 3D datorgrafik. Den innehåller 3D modellinformation som triangelnät, belysning, skuggning, rörelsedata, linjer och punkter med färg och struktur. Formatet accepterades som ECMA-363-standard i augusti 2005. 3D PDF-dokument stöder inbäddning av U3D objekt och kan visas i Adobe Reader (version 7 och senare). Formatet U3D utvecklades med syftet att skapa en universell standard för tredimensionell datalagring och utbyte. Formatet finner dock sin huvudsakliga användning vid kodning för 3D PDF snarare än att användas som ett utbytesformat. Acrobat 3D konverterar en 3D-filtyp som stöds till antingen U3D eller PRC vid konvertering till PDF.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera FBX till många andra filformat, inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-3ds/" name="FBX TILL 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-amf/" name="FBX TILL AMF" description="Additiv tillverkningsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-ase/" name="FBX TILL ASE" description="2D-animationsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-dae/" name="FBX TILL DAE" description="Digital Asset Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-gltf/" name="FBX TILL GLTF" description="GL-överföringsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-html/" name="FBX TILL HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-obj/" name="FBX TILL OBJ" description="3D Filformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-ply/" name="FBX TILL PLY" description="Polygon filformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-rvm/" name="FBX TILL RVM" description="AVEVA Plant Design Model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/fbx-to-stl/" name="FBX TILL STL" description="Utbytbar 3D ytgeometri" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}