﻿---
title: Convertire da PDF a STL tramite C# 
weight: 450
url: /it/net/conversion/pdf-to-stl/ 
description: Codice di esempio per la conversione da PDF a STL C#. Utilizza API codice di esempio per la conversione da PDF file batch a STL all'interno di VB.NET, Asp.NET o qualsiasi applicazione basata su .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertire da PDF a STL tramite C#" h2="Rendera PDF come STL senza alcun software di modellazione e rendering 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come convertire da PDF a STL usando C#" %}}

 Per convertire da PDF a STL, useremo
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API che è una piattaforma di conversione e manipolazione di documenti API ricca di funzionalità, potente e facile da usare per C#. Apri
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Gestore di pacchetti, ricerca di
 Aspose.3D 
 E installare. È inoltre possibile utilizzare il seguente comando dalla Console di Gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando Console Gestione pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passi per convertire da PDF a STL tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programmatori possono facilmente caricare e convertire PDF file in STL in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica PDF file tramite il costruttore della classe Scene1. Creare un'istanza di StlSaveOptions1. Imposta STL proprietà specifiche per la conversione avanzata1. Chiama il metodo Scena. Salva1. Passa il percorso di output con STL estensione file e oggetto di StlSaveOptions1. Controlla il file STL risultante nel percorso specificato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di conversione .NET, assicurati di avere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con .NET Framework, .NET Core, Mono.- Ambiente di sviluppo come Microsoft Visual Studio.- Aspose.3D for .NET DLL a cui si fa riferimento nel progetto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo codice di esempio mostra la conversione da PDF a STL C#" offSpacer="" %}}

```cs
// Caricare il PDF in un oggetto di scena 
var document = new Aspose.ThreeD.Scene("template.pdf");
// Creare un'istanza di StlSaveOptions 
var options = new Aspose.ThreeD.Formats.StlSaveOptions();
// Salva PDF come STL 
document.Save("output.stl", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App gratuita da convertire da PDF a STL" sectionDescription="Controlla le nostre demo live per [Conversione da PDF a STL](https://products.aspose.app/3d/conversion/pdf-to-stl) Con i seguenti vantaggi." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non c\' è bisogno di scaricare o configurare nulla." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\' è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il tuo file PDF e premere il pulsante \"Converti\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai immediatamente il link per il download del file STL risultante." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Una libreria di elaborazione file 3D per manipolare 3D file senza alcun software di modellazione e rendering. Il 3D API supporta Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formati di file e altro ancora. Gli sviluppatori possono creare, leggere, convertire, modificare e controllare facilmente la sostanza di 3D formati di documenti.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable Document Format (PDF) è un tipo di documento creato da Adobe negli anni '90. Lo scopo di questo formato di file era introdurre uno standard per la rappresentazione di documenti e altro materiale di riferimento in un formato indipendente dal software applicativo, dall'hardware e dal sistema operativo. PDF file possono essere aperti anche in Adobe Acrobat Reader/Writer nella maggior parte dei browser moderni come Chrome, Safari, Firefox tramite estensioni/plug-in. La maggior parte delle suite software disponibili in commercio offre anche la conversione dei propri documenti in formato di file PDF senza la necessità di alcun componente software aggiuntivo. Pertanto, il formato di file PDF ha la piena capacità di contenere informazioni come testo, immagini, collegamenti ipertestuali, campi di modulo, rich media, firme digitali, allegati, metadati, funzionalità geospaziali e 3D oggetti in esso contenuti che possono diventare parte del documento di origine.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="stl" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL, abbreviazione di stereolithrography, è un formato di file intercambiabile che rappresenta la geometria della superficie tridimensionale. Il formato del file trova il suo utilizzo in diversi campi come la prototipazione rapida, la stampa 3D e la produzione assistita da computer. Rappresenta una superficie come una serie di piccoli triangoli, noti come sfaccettature, in cui ciascuna sfaccettatura è descritta da una direzione perpendicolare e tre punti che rappresentano i vertici del triangolo. I dati risultanti vengono utilizzati dalle applicazioni per determinare la sezione trasversale della forma 3D che deve essere costruita dal fabber. Non sono disponibili informazioni nel formato di file STL per la rappresentazione di colore, texture o altri attributi comuni del modello CAD.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire PDF in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-3ds/" name="Da PDF a 3DS" description="Mesh DOS da studio 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-amf/" name="Da PDF a AMF" description="Formato di produzione additiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-dae/" name="Da PDF a DAE" description="Scambio di beni digitali" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-fbx/" name="Da PDF a FBX" description="Formato 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-html/" name="Da PDF a HTML" description="Linguaggio di markup iper testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-obj/" name="Da PDF a OBJ" description="Formato file 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-ply/" name="Da PDF a PLY" description="Formato file poligono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-rvm/" name="Da PDF a RVM" description="Modello di progettazione di piante AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/pdf-to-u3d/" name="Da PDF a U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}