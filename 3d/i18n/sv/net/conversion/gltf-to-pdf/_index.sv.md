﻿---
title: Konvertera GLTF till PDF via C# 
url: /sv/net/conversion/gltf-to-pdf/ 
description: Provkod för GLTF till PDF C# konvertering. Använd API exempelkod för sats GLTF filer till PDF konvertering inom VB.NET, Asp.NET eller någon .NET baserad program.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera GLTF till PDF via C#" h2="Rendera GLTF som PDF utan någon 3D modellering och rendering programvara." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hur man konverterar GLTF till PDF använder C#" %}}

 För att konvertera GLTF till PDF använder vi oss av.
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API som är en funktionsrika, kraftfull och lättanvänd dokumentmanipulering och konvertering API för C#-plattform. ÖppnaName
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Pakethanterare, sök
 Aspose.3D 
 Och installera. Du kan också använda följande kommando från Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Pakethanterarens konsolkommandoComment" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera GLTF till PDF via C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programmerare kan enkelt ladda och konvertera GLTF filer till PDF på bara några få kodrader.

{{% /blocks/products/pf/agp/text %}}

1. Ladda GLTF- filen via konstruktören i scenens klass1. Skapa en instans av AmfSaveOptions1. Ange PDF specifika egenskaper för avancerad konvertering1. Ring scenen.Spara metoden.1. Passera utdata sökvägen med PDF filändelsen & objekt PdfSaveOptions.1. Kontrollera resulterande PDF- fil vid angiven sökväg.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör .NET konverteringskoden, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Kärna, Mono.- Utvecklingsmiljö som Microsoft Visual Studio.- Aspose.3D for .NET DLL refereras i ditt projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Den här koden visar GLTF till PDF C#" offSpacer="" %}}

```cs
// Ladda GLTF i ett objekt i Scene 
var document = new Aspose.ThreeD.Scene("template.gltf");
// Skapa en instans av PdfSaveOptionsName 
var options = new Aspose.ThreeD.Formats.PdfSaveOptions();
// Spara GLTF som en PDF 
document.Save("output.pdf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Gratis app för att konvertera GLTF till PDF" sectionDescription="Kolla våra live demos för [GLTF till PDF konvertering](https://products.aspose.app/3d/conversion/gltf-to-pdf) Med följande förmåner." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Ingen anledning att ladda ner eller installera något." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Bara ladda upp din GLTF-fil och tryck på knappen \"Konvertera\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer omedelbart att få nedladdningslänken för resulterande PDF-fil." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Ett 3D Filbehandlingsbibliotek för att manipulera 3D filer utan någon modellering och återgivningsprogram. 3D API stöder Discreet3DS, WavefrontOBJ, FBX (ASCII, binära), STL (ASCII, Binära), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco filformat med mera. Utvecklare kan enkelt skapa, läsa, konvertera, ändra och styra substansen i 3D dokumentformat.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (GL Transmission Format) är ett 3D filformat som lagrar 3D modell information i JSON-format. Användningen av JSON minimerar både storleken på 3D tillgångar och den körtidsbehandling som krävs för att packa upp och använda dessa tillgångar. Det antogs för effektiv överföring och lastning av 3D scener och modeller genom ansökningar. glTF utvecklades av Khronos Group 3D Formats Working Group och beskrivs också som JPEG av 3D av dess skapare. Formatet definierar en utökbar, gemensamt publiceringsformat för 3D innehållsverktyg och innehållstjänster som effektiviserar att utveckla arbetsflöden och möjliggör interoperabel användning av innehåll överst industrin. Avsikten bakom skapandet av glTF filformat var att definiera en extensibel, gemensamt publiceringsformat för 3D innehållsverktyg och innehållstjänster som ska effektivisera utvecklingen av arbetsflöden och möjliggöra interoperabel användning av innehåll på alla sätt industrin. Det minimerar körtidsbehandling av program som använder WebGL och andra API.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="pdf" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Bärbart dokumentformat (PDF) är en typ av dokument som skapats av Adobe under 1990-talet. Syftet med detta filformat var att införa en standard för framställning av dokument och annat referensmaterial i ett format som är oberoende av programvara. hårdvara och operativsystem. PDF filer kan öppnas i Adobe Acrobat Reader/Writer samt i de flesta moderna webbläsare som Chrome, Safari, Firefox via tillägg/kontakt. De flesta av de kommersiellt tillgängliga programvaran erbjuder också konvertering av sina dokument till PDF filformat utan krav på någon ytterligare programvarukomponent. Således har PDF filformat full förmåga att innehålla information som text, bilder, hyperlänkar, formfält, rika media, digitala signaturer, bilagor, metadata, geospatiella funktioner och 3D objekt som kan bli en del av källdokumentet.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}