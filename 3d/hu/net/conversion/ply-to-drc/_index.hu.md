﻿---
title: "PLY konvertálása DRC-re a következőn keresztül: C# "
url: /hu/net/conversion/ply-to-drc/ 
description: Mintakód a(z) PLY–DRC C# konverzióhoz. Használjon API példakódot a kötegelt PLY fájlok DRC konvertálásához VB.NET, Asp.NET vagy bármely .NET alapú alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="PLY konvertálása DRC-re a következőn keresztül: C#" h2="A(z) PLY megjelenítése DRC-ként 3D modellező és megjelenítő szoftver nélkül." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DRC" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PLY" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="PLY konvertálása DRC-re a C# használatával" %}}

 A(z) PLY DRC-re konvertálásához a következőt használjuk:
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, amely funkciókban gazdag, hatékony és könnyen használható dokumentumkezelési és -konverziós API a C# platformhoz. Nyisd ki
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 csomagkezelő, keressen
 Aspose.3D 
 és telepítse. A következő parancsot is használhatja a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Csomagkezelő konzolparancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Lépések a(z) PLY konvertálásához DRC-re a következőn keresztül: C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programozói könnyedén betölthetnek és konvertálhatnak PLY fájlt DRC formátumba, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. PLY fájl betöltése a Scene osztály konstruktorán keresztül1. Hozzon létre egy AmfSaveOptions példányt1. Állítson be DRC speciális tulajdonságot a speciális konverzióhoz1. Hívja a Scene.Save metódust1. Adja meg a kimeneti útvonalat DRC fájlkiterjesztéssel és a DrcSaveOptions objektumával1. Ellenőrizze a kapott DRC fájlt a megadott elérési úton
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A .NET konverziós kód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy egy kompatibilis operációs rendszer .NET Framework, .NET Core, Mono rendszerrel.- Fejlesztői környezet, például a Microsoft Visual Studio.- Aspose.3D for .NET DLL-re hivatkozik a projektben.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ez a mintakód PLY–DRC C# konverziót mutat" offSpacer="" %}}

```cs
// töltse be a(z) PLY elemet a jelenet egyik objektumába 
var document = new Aspose.ThreeD.Scene("template.ply");
// hozzon létre egy DrcSaveOptions példányt 
var options = new Aspose.ThreeD.Formats.DrcSaveOptions();
// PLY mentése DRC-ként 
document.Save("output.drc", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ingyenes alkalmazás a(z) PLY konvertálásához DRC-re" sectionDescription="Tekintse meg élő bemutatóinkat [PLY–DRC konverzió](https://products.aspose.app/3d/conversion/ply-to-drc) a következő előnyökkel." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nem kell letölteni vagy beállítani semmit." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel a(z) PLY fájlt, és nyomja meg a „Konvertálás” gombot." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Azonnal megkapja a letöltési linket az eredményül kapott DRC fájlhoz." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Egy 3D fájlfeldolgozó könyvtár 3D fájlok kezeléséhez modellező és megjelenítő szoftverek nélkül. A 3D API támogatja a következőt: Discreet3DS, WavefrontOBJ, FBX (ASCII, bináris), STL (ASCII, bináris), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco fájlformátumok és egyebek. A fejlesztők könnyedén hozhatnak létre, olvashatnak, konvertálhatnak, módosíthatnak és szabályozhatnak 3D dokumentumformátumokat.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}
A PLY, Polygon File Format, a 3D fájlformátumot képviseli, amely sokszögek gyűjteményeként leírt grafikus objektumokat tárol. Ennek a fájlformátumnak az volt a célja, hogy egy egyszerű és könnyű fájltípust hozzon létre, amely elég általános ahhoz, hogy a modellek széles körében hasznos legyen. A PLY fájlformátum ASCII és bináris formátumban is elérhető a kompakt tárolás, valamint a gyors mentés és betöltés érdekében. A fájlformátumot különböző alkalmazások használják, amelyek támogatják a 3D fájlok olvasását.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="drc" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
.drc kiterjesztésű fájl egy tömörített 3D fájlformátum, amelyet a Google Draco könyvtárral hoztak létre. A Google a(z) Draco-ot nyílt forráskódú könyvtárként kínálja 3D geometriai hálók és pontfelhők tömörítésére és kicsomagolására, valamint javítja a 3D grafikák tárolását és átvitelét. Kódolja a bemeneti adatokat, és .drc fájlként menti el. A fogadó oldalon a API beolvassa a .drc fájlokat, és ezeket PLY vagy OBJ fájlként tudja kiadni. A tömörített kimeneti fájl lehetővé teszi a felhasználók számára, hogy gyorsabban töltsenek le alkalmazásokat, és gyorsan betöltsék a 3D grafikát a böngészőkben.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A(z) PLY fájlt számos más fájlformátumra is konvertálhatja, köztük néhány alább felsorolt fájlformátumra." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-3ds/" name="PLY - 3DS" description="3D Studio DOS Mesh" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-amf/" name="PLY - AMF" description="Additív gyártási formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-dae/" name="PLY - DAE" description="Digitális Eszközcsere" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-fbx/" name="PLY - FBX" description="3D Formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-html/" name="PLY - HTML" description="Hyper Text Markup Language" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-obj/" name="PLY - OBJ" description="3D Fájlformátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-pdf/" name="PLY - PDF" description="Hordozható dokumentum formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-rvm/" name="PLY - RVM" description="AVEVA üzemtervezési modell" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-stl/" name="PLY - STL" description="Cserélhető 3D felületi geometria" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-u3d/" name="PLY - U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}