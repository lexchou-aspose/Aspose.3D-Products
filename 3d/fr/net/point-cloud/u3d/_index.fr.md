﻿---
title: Générer un nuage de points aux formats de fichier U3D via .NET 
weight: 830
url: /fr/net/point-cloud/u3d/ 
description: C# code source pour charger, rendre et ajouter générer un nuage de points à U3D documents sur .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Générer un nuage de points vers U3D via C#" h2="Créez vos propres applications .NET pour générer des nuages de points vers des fichiers U3D à l\'aide d\'API côté serveur." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="U3D" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment générer un nuage de points dans un fichier U3D à l\'aide de C#" %}}

 Afin de générer un nuage de points dans le fichier U3D, nous utiliserons
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API qui est une plate-forme riche en fonctionnalités, puissante et facile à utiliser API pour C# à utiliser avec générer un nuage de points. Ouvrir
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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour générer un nuage de points vers U3D via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D permet aux développeurs de générer facilement un nuage de points dans le fichier U3D avec seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

- Charger le fichier U3D via le constructeur de la classe Scene- Obtenir l'objet nuage de points de Aspose.3D- Créer un objet de transformation via la méthode EvaluateGlobalTransform- Générer un nuage de points à l'aide de la méthode Merge- Appelez la méthode Scene.Save avec l'objet
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET est pris en charge sur tous les principaux systèmes d'exploitation. Assurez-vous simplement que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec .NET Framework, .NET Core, Mono- Environnement de développement comme Microsoft Visual Studio- Aspose.3D for .NET référencé dans votre projet
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Code C# pour générer un nuage de points vers U3D" offSpacer="" %}}

```cs

//Le fichier source qui doit générer le nuage de points
string file = "template.u3d";

// créer une instance de Scene
Scene scene = new Scene(file);

//Obtenez l'objet nuage de points de Aspose.3D et générez un nuage de points
var pc = new PointCloud();
scene.RootNode.Accept((Node n) =>
{
    if (n.Entities.Count > 0)
    {
        var transform = n.EvaluateGlobalTransform(true);
        foreach (var entity in n.Entities)
        {
            if (entity is Geometry g)
            {
                Merge(pc, g, transform);
            }
            else if (entity is IMeshConvertible mc)
            {
                var mesh = mc.ToMesh();
                Merge(pc, mesh, transform);
            }

        }
    }
    return true;
});

//Méthode de fusion pour générer des nuages de points
private void Merge(PointCloud pc, Geometry g, Matrix4 transform)
{
    var tmp = PointCloud.FromGeometry(g, 10);
    for (int i = 0; i < tmp.ControlPoints.Count; i++)
    {
        var pt = transform * tmp.ControlPoints[i];
        pc.ControlPoints.Add(pt);
    }
}

// créer une instance de newScene
var newScene = new Scene(pc);

//Lors de l'enregistrement, vous devez créer un objet SaveOptions du format d'enregistrement
string output=System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".ply";
PlySaveOptions ply = new PlySaveOptions();
ply.PointCloud = true;
newScene.Save(output,ply);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="À propos de Aspose.3D for .NET API" %}}

 Aspose.3D est un CAD et un Gameware API pour charger, modifier et convertir des fichiers 3D. API est autonome et ne nécessite aucun logiciel de modélisation ou de rendu 3D. On peut facilement utiliser API pour Discreet3DS, WavefrontOBJ, STL (ASCII, Binaire), Universal3D, FBX (ASCII, Binaire), Collada, glTF, PLY, GLB, DirectX et d'autres formats. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Application gratuite pour générer un nuage de points vers U3D" sectionDescription="Consultez nos démos en direct pour [Nuage de points 3DS](https://products.aspose.app/3d/point-cloud/u3d) avec les avantages suivants." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger ou de configurer quoi que ce soit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire ou de compiler du code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement le fichier U3D et cliquez sur le bouton \"Générer\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Téléchargez le fichier U3D à partir du lien, si nécessaire" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}
U3D (Universal 3D) est un format de fichier compressé et une structure de données pour l'infographie 3D. Il contient 3D des informations sur le modèle telles que les maillages triangulaires, l'éclairage, l'ombrage, les données de mouvement, les lignes et les points avec couleur et structure. Le format a été accepté en tant que norme ECMA-363 en août 2005. 3D PDF documents prennent en charge l'incorporation de U3D objets et peuvent être visualisés dans Adobe Reader (version 7 et ultérieure).

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autre application prise en charge pour générer des nuages de points aux formats" subTitle="En utilisant C#, One peut également générer un nuage de points dans de nombreux autres formats de fichiers, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/3mf/" name="3MF" description="3D Format de fabrication" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/amf/" name="AMF" description="Format de fabrication additive" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/ase/" name="ASE" description="Fichier d\'animation 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/dae/" name="DAE" description="Échange d\'actifs numériques" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/dxf/" name="DXF" description="Format d\'échange de dessin" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/fbx/" name="FBX" description="Format 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/glb/" name="GLB" description="3D Représentation binaire du fichier" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/gltf/" name="GLTF" description="Format de transmission GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/jt/" name="JT" description="Fichier de tessellation Jupiter" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/obj/" name="OBJ" description="3D Format de fichier" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/ply/" name="PLY" description="Format de fichier polygone" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/rvm/" name="RVM" description="Modèle de conception d\'usine AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/stl/" name="STL" description="Géométrie de surface 3D interchangeable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/3ds/" name="3DS" description="3D Format de fichier Studio Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/vrml/" name="VRML" description="Langage de modélisation de réalité virtuelle" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/x/" name="X" description="Image du modèle DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/usd/" name="USD" description="Description de la scène universelle" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/usdz/" name="USDZ" description="Description de la scène universelle Archive Zip" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}