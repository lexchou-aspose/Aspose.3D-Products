﻿---
title: "OBJ konvertálása STL-re a következőn keresztül: C# "
weight: 3370
url: /hu/net/conversion/obj-to-stl/ 
description: Mintakód a(z) OBJ–STL C# konverzióhoz. Használjon API példakódot a kötegelt OBJ fájlok STL konvertálásához VB.NET, Asp.NET vagy bármely .NET alapú alkalmazáson belül.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="OBJ konvertálása STL-re a következőn keresztül: C#" h2="A(z) OBJ megjelenítése STL-ként 3D modellező és megjelenítő szoftver nélkül." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="OBJ konvertálása STL-re a C# használatával" %}}

 A(z) OBJ STL-re konvertálásához a következőt használjuk:
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

{{% blocks/products/pf/agp/feature-section-col title="Lépések a(z) OBJ konvertálásához STL-re a következőn keresztül: C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programozói könnyedén betölthetnek és konvertálhatnak OBJ fájlt STL formátumba, mindössze néhány sornyi kóddal.

{{% /blocks/products/pf/agp/text %}}

1. OBJ fájl betöltése a Scene osztály konstruktorán keresztül1. Hozzon létre egy StlSaveOptions példányt1. Állítson be STL speciális tulajdonságot a speciális konverzióhoz1. Hívja a Scene.Save metódust1. Adja meg a kimeneti útvonalat STL fájlkiterjesztéssel és az StlSaveOptions objektumával1. Ellenőrizze a kapott STL fájlt a megadott elérési úton
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A .NET konverziós kód futtatása előtt győződjön meg arról, hogy rendelkezik a következő előfeltételekkel.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy egy kompatibilis operációs rendszer .NET Framework, .NET Core, Mono rendszerrel.- Fejlesztői környezet, például a Microsoft Visual Studio.- Aspose.3D for .NET DLL-re hivatkozik a projektben.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ez a mintakód OBJ–STL C# konverziót mutat" offSpacer="" %}}

```cs
// töltse be a(z) OBJ elemet a jelenet egyik objektumába 
var document = new Aspose.ThreeD.Scene("template.obj");
// hozzon létre egy StlSaveOptions példányt 
var options = new Aspose.ThreeD.Formats.StlSaveOptions();
// OBJ mentése STL-ként 
document.Save("output.stl", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ingyenes alkalmazás a(z) OBJ konvertálásához STL-re" sectionDescription="Tekintse meg élő bemutatóinkat [OBJ–STL konverzió](https://products.aspose.app/3d/conversion/obj-to-stl) a következő előnyökkel." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nem kell letölteni vagy beállítani semmit." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltse fel a(z) OBJ fájlt, és nyomja meg a „Konvertálás” gombot." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Azonnal megkapja a letöltési linket az eredményül kapott STL fájlhoz." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Egy 3D fájlfeldolgozó könyvtár 3D fájlok kezeléséhez modellező és megjelenítő szoftverek nélkül. A 3D API támogatja a következőt: Discreet3DS, WavefrontOBJ, FBX (ASCII, bináris), STL (ASCII, bináris), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco fájlformátumok és egyebek. A fejlesztők könnyedén hozhatnak létre, olvashatnak, konvertálhatnak, módosíthatnak és szabályozhatnak 3D dokumentumformátumokat.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
OBJ fájlokat használ a Wavefront Advanced Visualizer alkalmazása a geometriai objektumok meghatározására és tárolására. A geometriai adatok vissza- és előre továbbítása OBJ fájlon keresztül lehetséges. A OBJ formátum támogatja mind a sokszögű geometriát, mint a pontok, vonalak, textúra csúcsok, lapok és a szabad formájú geometria (görbék és felületek). Ez a formátum nem támogatja az animációt vagy a fényre és a jelenetek helyzetére vonatkozó információkat. A OBJ fájl általában a CAD (számítógéppel segített tervezés) által generált 3D modellezési folyamat végterméke. A csúcsok tárolásának alapértelmezett sorrendje az óramutató járásával ellentétes, elkerülve az arcnormálok kifejezett deklarálását. Bár OBJ fájl egy megjegyzéssorban deklarálja a léptékinformációkat, mégsem lettek deklarálva mértékegységek OBJ koordinátákhoz.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="stl" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL, a sztereolitrográfia rövidítése, egy felcserélhető fájlformátum, amely háromdimenziós felületi geometriát képvisel. A fájlformátumot számos területen használják, például a gyors prototípuskészítésben, a 3D nyomtatásban és a számítógéppel segített gyártásban. A felületet kis háromszögek sorozataként ábrázolja, amelyeket lapoknak nevezünk, ahol minden oldalt egy merőleges irány és három pont ír le, amelyek a háromszög csúcsait képviselik. A kapott adatokat az alkalmazások arra használják, hogy meghatározzák a fabber által megépítendő 3D alakzat keresztmetszetét. A STL fájlformátumban nem áll rendelkezésre információ a színek, textúrák vagy más általános CAD modell attribútumok megjelenítéséhez.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="A(z) OBJ fájlt számos más fájlformátumra is konvertálhatja, köztük néhány alább felsorolt fájlformátumra." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-3ds/" name="OBJ - 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-amf/" name="OBJ - AMF" description="Additív gyártási formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-dae/" name="OBJ - DAE" description="Digitális Eszközcsere" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-fbx/" name="OBJ - FBX" description="3D Formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-html/" name="OBJ - HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-pdf/" name="OBJ - PDF" description="Hordozható dokumentum formátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-ply/" name="OBJ - PLY" description="Sokszög fájlformátum" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-rvm/" name="OBJ - RVM" description="AVEVA üzemtervezési modell" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/obj-to-u3d/" name="OBJ - U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}