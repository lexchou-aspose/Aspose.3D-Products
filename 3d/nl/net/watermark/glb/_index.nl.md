﻿---
title: Blind watermerk toevoegen aan GLB bestandsindelingen via .NET 
weight: 830
url: /nl/net/watermark/glb/ 
description: C# broncode om blind watermerk te laden, weer te geven en toe te voegen aan GLB documenten op .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Blind watermerk toevoegen aan GLB via C#" h2="Bouw uw eigen .NET apps om GLB bestanden van een watermerk te voorzien met behulp van server-side API\'s." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Watermerken naar GLB-bestanden met C#" %}}

 Om het GLB bestand van een watermerk te voorzien, gebruiken we
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, een veelzijdig, krachtig en gebruiksvriendelijk API voor C#-platform dat kan worden gebruikt met het toevoegen van een watermerk. Open
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 pakketbeheerder, zoek naar
 **Aspose.3D** 
 en installeren. U kunt ook de volgende opdracht gebruiken vanuit de Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Pakketbeheer Console-opdracht" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Stappen om blind watermerk toe te voegen aan GLB via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D maakt het de ontwikkelaars gemakkelijk om met slechts enkele regels code een blind watermerk aan het GLB-bestand toe te voegen.

{{% /blocks/products/pf/agp/text %}}

- Laad GLB bestand via de constructor van Scene klasse- Haal de mesh-klasse van Aspose.3D op- Voeg watermerk en wachtwoord toe met behulp van de EncodeWatermark-methode van Aspose.3D- Roep de Scene.Save-methode aan met object
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="systeem vereisten" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET wordt ondersteund op alle belangrijke besturingssystemen. Zorg ervoor dat u aan de volgende vereisten voldoet.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows of een compatibel besturingssysteem met .NET Framework, .NET Core, Mono- Ontwikkelomgeving zoals Microsoft Visual Studio- Aspose.3D for .NET waarnaar wordt verwezen in uw project
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code om blind watermerk toe te voegen aan GLB" offSpacer="" %}}

```cs

//Het bronbestand dat van een watermerk moet worden voorzien en het uitvoerbestand na het opslaan
string file = "template.glb";
string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

// maak een instantie van Scene
Scene scene = new Scene(file);

//Watermerk en wachtwoord toevoegen aan bestanden
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

//Sla het bestand op in de gewenste indeling
scene.Save(output, FileFormat.FBX7400ASCII);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Over Aspose.3D for .NET API" %}}

 Aspose.3D is een CAD en Gameware API om 3D-bestanden te laden, aan te passen en te converteren. API is een standalone en vereist geen 3D-modellerings- of renderingsoftware. Men kan gemakkelijk API gebruiken voor Discreet3DS, WavefrontOBJ, STL (ASCII, Binair), Universal3D, FBX (ASCII, Binair), Collada, glTF, PLY, GLB, DirectX en meer formaten. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

 {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Gratis app om blind watermerk toe te voegen aan GLB" sectionDescription="Bekijk onze live demo\'s om [Watermerk GLB](https://products.aspose.app/3d/watermark/glb) met volgende voordelen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" U hoeft niets te downloaden of in te stellen" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" U hoeft geen code te schrijven of te compileren" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Upload gewoon GLB bestand en klik op de knop \"Watermerk\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download GLB bestand via de link, indien nodig" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}
GLB is de binaire bestandsindeling van 3D modellen die zijn opgeslagen in het GL-transmissieformaat (glTF). Informatie over 3D modellen zoals knooppunthiërarchie, camera's, materialen, animaties en meshes in binair formaat. Deze binaire indeling slaat het glTF-item (JSON, .bin en afbeeldingen) op in een binaire blob. Het vermijdt ook het probleem van een toename van de bestandsgrootte die optreedt in het geval van glTF. GLB bestandsformaat resulteert in compacte bestandsgroottes, snel laden, complete 3D scèneweergave en uitbreidbaarheid voor verdere ontwikkeling. Het formaat gebruikt model/gltf-binary als MIME-type.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere ondersteunde app om blind watermerk aan formaten toe te voegen" subTitle="Met behulp van C# kan men ook een blind watermerk toevoegen aan vele andere bestandsindelingen, waaronder." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3mf/" name="3MF" description="3D Productie-indeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/amf/" name="AMF" description="Additief productieformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/ase/" name="ASE" description="2D-animatiebestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dae/" name="DAE" description="Digitale activauitwisseling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dxf/" name="DXF" description="Tekening uitwisselingsformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/fbx/" name="FBX" description="3D Formaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3ds/" name="3DS" description="3D Studio Mesh-bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/gltf/" name="GLTF" description="GL-verzendformaat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/jt/" name="JT" description="Jupiter Tessellation-bestand" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/obj/" name="OBJ" description="3D Bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/ply/" name="PLY" description="Polygoon-bestandsindeling" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/rvm/" name="RVM" description="AVEVA Plant Design Model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/stl/" name="STL" description="Verwisselbare 3D oppervlaktegeometrie" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/vrml/" name="VRML" description="Virtual Reality-modelleringstaal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/x/" name="X" description="DirectX-modelafbeelding" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usd/" name="USD" description="Universele scènebeschrijving" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usdz/" name="USDZ" description="Universele scènebeschrijving Zip-archief" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}