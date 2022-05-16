﻿---
title: Afficher les formats de fichier GLTF via .NET 
weight: 2640
url: /fr/net/viewer/gltf/ 
description: C# code source pour charger, restituer et afficher GLTF documents sur .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="GLTF Visionneuse de fichiers for .NET" h2="Rendez les fichiers GLTF sans aucun logiciel de modélisation et de rendu 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment afficher le fichier GLTF à l\'aide de C#" %}}

 Pour afficher le fichier GLTF, nous utiliserons
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API qui est une plate-forme riche en fonctionnalités, puissante et facile à utiliser API pour C# à utiliser avec n'importe quelle visionneuse. Ouvrir
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 gestionnaire de paquets, recherchez
 **Aspose.3D** 
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console du gestionnaire de packages.

{{% blocks/products/pf/agp/code-block title="Commande de la console du gestionnaire de packages" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour afficher GLTF via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D permet aux développeurs d'afficher facilement le fichier GLTF avec seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

1. Charger le fichier GLTF via le constructeur de la classe Scene1. Créer une instance de Html5SaveOptions1. Définir les propriétés du formatage avancé1. Appelez la méthode Scene.Save avec l'objet de Html5SaveOptions1. Vérifiez le fichier HTML résultant dans le navigateur par défaut
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET est pris en charge sur tous les principaux systèmes d'exploitation. Assurez-vous simplement que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec .NET Framework, .NET Core, Mono- Environnement de développement comme Microsoft Visual Studio- Aspose.3D for .NET référencé dans votre projet
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code pour afficher GLTF" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// charger GLTF scène via une instance de Scene
var scene = new ThreeD.Scene("template.gltf");
// créer un objet de Html5SaveOptions et définir les propriétés de formatage
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // éteindre la grille
    ShowGrid = false,
    // désactiver l'interface utilisateur
    ShowUI = false
};

// enregistrer 3D scène sous HTML5
scene.Save(output, options);
// charger le résultat HTML dans le navigateur par défaut
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="À propos de Aspose.3D for .NET API" %}}

 Aspose.3D est un CAD et un Gameware API pour charger, modifier et convertir des fichiers 3D. API est autonome et ne nécessite aucun logiciel de modélisation ou de rendu 3D. On peut facilement utiliser API pour Discreet3DS, WavefrontOBJ, STL (ASCII, Binaire), Universal3D, FBX (ASCII, Binaire), Collada, glTF, PLY, GLB, DirectX et d'autres formats. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Application gratuite pour afficher GLTF" sectionDescription="Consultez nos démos en direct pour [Afficher GLTF](https://products.aspose.app/3d/viewer/gltf) avec les avantages suivants." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger ou de configurer quoi que ce soit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire ou de compiler du code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement le fichier GLTF et appuyez sur le bouton \"Afficher\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Téléchargez le fichier GLTF à partir du lien, si nécessaire" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (GL Transmission Format) est un format de fichier 3D qui stocke les informations de modèle 3D au format JSON. L'utilisation de JSON minimise à la fois la taille des actifs 3D et le traitement d'exécution nécessaire pour décompresser et utiliser ces actifs. Il a été adopté pour la transmission et le chargement efficaces de 3D scènes et modèles par les applications. glTF a été développé par le groupe de travail sur les formats 3D du groupe Khronos et est également décrit comme JPEG de 3D par ses créateurs. Le format définit un format de publication extensible et commun pour les outils et services de contenu 3D qui rationalise les workflows de création et permet une utilisation interopérable du contenu dans l'ensemble du secteur. L'intention derrière la création du format de fichier glTF était de définir un format de publication extensible et commun pour les outils et services de contenu 3D qui devrait rationaliser les workflows de création et permettre une utilisation interopérable du contenu dans l'industrie. Il minimise le traitement d'exécution par les applications utilisant WebGL et d'autres API.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de visionneuse pris en charge" subTitle="À l\'aide de C#, on peut également afficher de nombreux autres formats de fichiers, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Maillage Studio DOS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D Format de fabrication" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="Format de fabrication additive" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="Fichier d\'animation 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="Échange d\'actifs numériques" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="Format d\'échange de dessin" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="Format 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D Représentation binaire du fichier" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="Fichier de tessellation Jupiter" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D Format de fichier" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="Format de fichier polygone" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="Modèle de conception d\'usine AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="Géométrie de surface 3D interchangeable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="Langage de modélisation de réalité virtuelle" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="X" description="Image du modèle DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP Format d\'archivage" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}