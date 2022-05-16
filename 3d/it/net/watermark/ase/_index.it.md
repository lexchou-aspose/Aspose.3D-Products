﻿---
title: Aggiungi filigrana cieca a ASE formati di file tramite .NET 
weight: 830
url: /it/net/watermark/ase/ 
description: C# codice sorgente per caricare, eseguire il rendering e aggiungere filigrana cieca a ASE documenti su .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Aggiungi filigrana cieca a ASE tramite C#" h2="Crea le tue .NET app per filigranare i file ASE utilizzando le API lato server." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ASE" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come filigranare su ASE file utilizzando C#" %}}

 Per filigranare il file ASE, utilizzeremo
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API che è una piattaforma API per C# ricca di funzionalità, potente e facile da usare da utilizzare con l'aggiunta di filigrane. Aprire
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 gestore pacchetti, cerca
 **Aspose.3D** 
 e installa. È inoltre possibile utilizzare il seguente comando dalla Console di gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando della console di gestione dei pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per aggiungere una filigrana cieca a ASE tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D consente agli sviluppatori di aggiungere facilmente una filigrana cieca al file ASE con poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

- Carica il file ASE tramite il costruttore della classe Scene- Ottieni la classe mesh di Aspose.3D- Aggiungi filigrana e password utilizzando il metodo EncodeWatermark di Aspose.3D- Chiama il metodo Scene.Save con l'oggetto
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET è supportato su tutti i principali sistemi operativi. Assicurati solo di avere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con .NET Framework, .NET Core, Mono- Ambiente di sviluppo come Microsoft Visual Studio- Aspose.3D for .NET referenziato nel tuo progetto
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# codice per aggiungere una filigrana cieca a ASE" offSpacer="" %}}

```cs

//Il file di origine che deve essere contrassegnato con la filigrana e il file di output dopo il salvataggio
string file = "template.ase";
string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

// creare un'istanza di Scene
Scene scene = new Scene(file);

//Aggiungi filigrana e password ai file
var numMeshes = 0;
scene.RootNode.Accept((Node node) =>
{
    var mesh = node.GetEntity<Mesh>();
    if (mesh != null)
    {
        numMeshes++;
        mesh = Watermark.EncodeWatermark(mesh, "HelloWorld", "1234");
        if (mesh != null)
        {
            node.Entity = mesh;
        }
    }
    return true;
});

//Salva il file nel formato che desideri
scene.Save(output, FileFormat.FBX7400ASCII);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Circa Aspose.3D for .NET API" %}}

 Aspose.3D è un CAD e un Gameware API per caricare, modificare e convertire 3D file. API è autonomo e non richiede alcun 3D software di modellazione o rendering. Si può facilmente usare API per Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX e altri formati. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App gratuita per aggiungere filigrana cieca a ASE" sectionDescription="Controlla le nostre demo dal vivo su [Filigrana ASE](https://products.aspose.app/3d/watermark/ase) con i seguenti vantaggi." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non è necessario scaricare o configurare nulla" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\'è bisogno di scrivere o compilare codice" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il file ASE e premere il pulsante \"Filigrana\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Scarica il file ASE dal link, se necessario" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}
Un file ASE è un'animazione o grafica 2D che contiene livelli, cornici, tavolozze, tag e impostazioni.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}



<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre app supportate per aggiungere filigrana cieca ai formati" subTitle="Utilizzando C#, si può anche aggiungere filigrana cieca a molti altri formati di file, tra cui." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3mf/" name="3MF" description="3D Formato di produzione" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/amf/" name="AMF" description="Formato di produzione additiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3ds/" name="3DS" description="3D Formato file mesh di Studio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dae/" name="DAE" description="Scambio di risorse digitali" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dxf/" name="DXF" description="Formato di scambio di disegni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/fbx/" name="FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/glb/" name="GLB" description="3D Rappresentazione binaria di file" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/gltf/" name="GLTF" description="Formato di trasmissione GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/jt/" name="JT" description="File di tassellazione di Giove" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/obj/" name="OBJ" description="3D Formato file" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/ply/" name="PLY" description="Formato file poligono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/rvm/" name="RVM" description="Modello AVEVA Plant Design" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/stl/" name="STL" description="Geometria della superficie 3D intercambiabile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/vrml/" name="VRML" description="Linguaggio di modellazione della realtà virtuale" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/x/" name="X" description="Immagine del modello DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usd/" name="USD" description="Descrizione della scena universale" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usdz/" name="USDZ" description="Descrizione scena universale Archivio zip" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}