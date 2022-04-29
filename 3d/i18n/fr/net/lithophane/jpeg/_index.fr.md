﻿---
title: Créez votre Lithophane à partir des formats de fichiers JPEG via .NET 
weight: 830
url: /fr/net/lithophane/jpeg/ 
description: C# code source pour charger, restituer et créer vos documents lithophane en JPEG sur .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Créez votre Lithophane en JPEG via C#" h2="Créez vos propres applications .NET pour créer vos fichiers lithophane vers JPEG à l\'aide d\'API côté serveur." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JPEG" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPEG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JPEG" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment créer votre fichier Lithophane en JPEG à l\'aide de C#" %}}

 Afin de créer votre fichier lithophane en JPEG, nous utiliserons
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API qui est une plate-forme API pour C# riche en fonctionnalités, puissante et facile à utiliser pour créer votre lithophane. Ouvrir
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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour créer votre Lithophane au format JPEG via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D permet aux développeurs de créer facilement votre lithophane dans le fichier JPEG avec seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

- Créez de nouveaux paramètres et créez un objet Mesh- Effectuer des opérations de calcul sur des objets Mesh- Le fichier JPEG charge la scène 3D via la classe Mesh- Appelez la méthode Scene.Save avec l'objet
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET est pris en charge sur tous les principaux systèmes d'exploitation. Assurez-vous simplement que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec .NET Framework, .NET Core, Mono- Environnement de développement comme Microsoft Visual Studio- Aspose.3D for .NET référencé dans votre projet
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code pour créer votre Lithophane en JPEG" offSpacer="" %}}

```cs

//L'image originale qui doit être téléchargée et la sortie du fichier 3d après l'enregistrement
    string file = "template.jpeg";
    string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

//Créer de nouveaux paramètres
    var td= TextureData.FromFile(file);
    const float nozzleSize = 0.9f;//0,2 mm
    const float layerHeight = 0.2f;
    var grayscale = ToGrayscale(td);
    const float width = 120.0f;//la largeur de la toile est de 200,0 mm
    float height = width / td.Width * td.Height;
    float thickness = 10.0f;//10 mm d'épaisseur
    float layers = thickness / layerHeight;
    int widthSegs = (int)Math.Floor(width / nozzleSize);
    int heightSegs = (int)Math.Floor(height / nozzleSize);

//Effectuer des opérations de calcul sur des objets Mesh
    var mesh = new Mesh();
    for (int y = 0; y < heightSegs; y++)
    {
        float dy = (float)y / heightSegs;
        for (int x = 0; x < widthSegs; x++)
        {
            float dx = (float)x / widthSegs;
            float gray = Sample(grayscale, td.Width, td.Height, dx, dy);
            float v = (1 - gray) * thickness;
            mesh.ControlPoints.Add(new Vector4(dx * width, dy * height, v));
        }
    }


    for (int y = 0; y < heightSegs - 1; y++)
    {
        int row = (y * heightSegs);
        int ptr = row;
        for (int x = 0; x < widthSegs - 1; x++)
        {
            mesh.CreatePolygon(ptr, ptr + widthSegs, ptr + 1);
            mesh.CreatePolygon(ptr + 1, ptr + widthSegs, ptr + widthSegs + 1);
            ptr++;
        }
    }

//Générer une scène 3D et enregistrer des objets
    var scene = new Scene(mesh);
    scene.Save(output, FileFormat.FBX7400ASCII);

//L'exemple de méthode à appeler
    static float Sample(float[,] data, int w, int h, float x, float y)
    {
        return data[(int)(x * w), (int)(y * h)];
    }

//Méthode ToGrayscale à appeler
    static float[,] ToGrayscale(TextureData td)
    {
        var ret = new float[td.Width, td.Height];
        var stride = td.Stride;
        var data = td.Data;
        var bytesPerPixel = td.BytesPerPixel;
        for (int y = 0; y < td.Height; y++)
        {
            int ptr = y * stride;
            for (int x = 0; x < td.Width; x++)
            {
                var v = (data[ptr] * 0.21f + data[ptr + 1] * 0.72f + data[ptr + 2] * 0.07f) / 255.0f;
                ret[x, y] = v;
                ptr += bytesPerPixel;
            }
        }
        return ret;
    }

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="À propos de Aspose.3D for .NET API" %}}

 Aspose.3D est un CAD et un Gameware API pour charger, modifier et convertir des fichiers 3D. API est autonome et ne nécessite aucun logiciel de modélisation ou de rendu 3D. On peut facilement utiliser API pour Discreet3DS, WavefrontOBJ, STL (ASCII, Binaire), Universal3D, FBX (ASCII, Binaire), Collada, glTF, PLY, GLB, DirectX et d'autres formats. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Application gratuite pour créer votre Lithophane au format JPEG" sectionDescription="Consultez nos démos en direct pour [Lithophane JPEG](https://products.aspose.app/3d/lithophane/JPEG) avec les avantages suivants." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger ou de configurer quoi que ce soit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire ou de compiler du code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement le fichier JPEG et appuyez sur le bouton \"lithophane\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Téléchargez le fichier JPEG à partir du lien, si nécessaire" >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autre application prise en charge pour créer votre lithophane aux formats" subTitle="À l\'aide de C#, on peut également créer votre lithophane dans de nombreux autres formats de fichiers, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/jpg/" name="JPG" description="Groupe mixte d\'experts photographiques" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/png/" name="PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/tga/" name="TGA" description="Adaptateur raster avancé Truevision" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/bmp/" name="BMP" description="Bitmap" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/gif/" name="GIF" description="Format d\'échange graphique" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/tiff/" name="TIFF" description="Format de fichier d\'image balisé" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}