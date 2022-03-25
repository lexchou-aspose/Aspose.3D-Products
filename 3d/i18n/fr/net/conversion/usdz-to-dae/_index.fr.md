---
title: Convertir USDZ en DAE via C# 
description: Convertir USDZ et d'autres fichiers 3D en utilisant .NET API
url: /fr/net/conversion/usdz-to-dae/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: DAE
otherformats: DRC HTML DAE ASE STL PLY 3MF OBJ 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir USDZ en DAE via C#" h2="Exportez USDZ et d\'autres fichiers 3D à l\'aide de .NET Framework, .NET Core et Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportez USDZ scène comme DAE avec C#" %}}
1. Charger le fichier USDZ en utilisant un constructeur de [Scène](https://apireference.aspose.com/3d/net/aspose.threed/scene) Classe2. Appel [Scène. Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Méthode
3. Passer le nom du fichier de sortie avec. Extension de dae comme premier paramètre
4. Spécifiez la valeur du champ 'Collada' à partir de [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Classe
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D conversion de format API for .NET" %}}
Installez à partir de la ligne de commande en tant que «nuget install Aspose.3d» ou via la console du gestionnaire de packages de Visual Studio avec «Installer-Package Aspose.3D»».

Vous pouvez également obtenir l'installateur MSI hors ligne ou DLLs dans un fichier ZIP à partir de [Téléchargements](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code pour la conversion de USDZ à DAE" gistPath="" %}}
```cs
// Charger le USDZ dans un objet de la scène 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// Enregistrer USDZ en tant que DAE 
scene.Save("output.dae", Aspose.ThreeD.FileFormat.Collada);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}