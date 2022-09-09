---
title: Convertir USDZ en JT via C# 
description: Convertissez USDZ et d'autres fichiers 3D à l'aide de .NET API
url: /fr/net/conversion/usdz-to-jt/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: JT
otherformats: JT PDF DXF ASE GLTF DRC DAE HTML 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir USDZ en JT via C#" h2="Exportez USDZ et d\'autres fichiers 3D à l\'aide de .NET Framework, .NET Core et Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exporter USDZ Scène en tant que JT avec C#" %}}
1. Charger le fichier USDZ en utilisant un constructeur de [Scène](https://apireference.aspose.com/3d/net/aspose.threed/scene) classe2. Appel [Scène.Enregistrer](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) méthode
3. Passez le nom du fichier de sortie avec l'extension .jt comme premier paramètre
4. Spécifiez la valeur du champ `SiemensJT9` à partir de [Format de fichier](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) classe
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Conversion de formats API for .NET" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.3d``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.3D```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code pour la conversion USDZ à JT" gistPath="" %}}
```cs
// charger le USDZ dans un objet de Scene 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// enregistrer USDZ en tant que JT 
scene.Save("output.jt", Aspose.ThreeD.FileFormat.SiemensJT9);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}