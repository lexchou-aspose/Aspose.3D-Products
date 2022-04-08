---
title: Convertir USDZ en PLY via C# 
description: Convertissez USDZ et d'autres fichiers 3D à l'aide de .NET API
url: /fr/net/conversion/usdz-to-ply/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: PLY
otherformats: AMF DRC HTML FBX DAE ASE JT RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir USDZ en PLY via C#" h2="Exportez USDZ et d\'autres fichiers 3D à l\'aide de .NET Framework, .NET Core et Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exporter USDZ Scène en tant que PLY avec C#" %}}
1. Charger le fichier USDZ en utilisant un constructeur de [Scène](https://apireference.aspose.com/3d/net/aspose.threed/scene) classe2. Appel [Scène.Enregistrer](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) méthode
3. Passez le nom du fichier de sortie avec l'extension .ply comme premier paramètre
4. Spécifiez la valeur du champ `PLY` à partir de [Format de fichier](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) classe
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Conversion de formats API for .NET" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.3d``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.3D```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code pour la conversion USDZ à PLY" gistPath="" %}}
```cs
// charger le USDZ dans un objet de Scene 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// enregistrer USDZ en tant que PLY 
scene.Save("output.ply", Aspose.ThreeD.FileFormat.PLY);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}