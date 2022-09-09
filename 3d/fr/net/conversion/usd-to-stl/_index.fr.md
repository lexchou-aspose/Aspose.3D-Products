---
title: Convertir USD en STL via C# 
description: Convertissez USD et d'autres fichiers 3D à l'aide de .NET API
url: /fr/net/conversion/usd-to-stl/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: STL
otherformats: OBJ DXF DAE DRC RVM STL ASE FBX 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir USD en STL via C#" h2="Exportez USD et d\'autres fichiers 3D à l\'aide de .NET Framework, .NET Core et Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exporter USD Scène en tant que STL avec C#" %}}
1. Charger le fichier USD en utilisant un constructeur de [Scène](https://apireference.aspose.com/3d/net/aspose.threed/scene) classe2. Appel [Scène.Enregistrer](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) méthode
3. Passez le nom du fichier de sortie avec l'extension .stl comme premier paramètre
4. Spécifiez la valeur du champ `STLASCII` à partir de [Format de fichier](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) classe
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Conversion de formats API for .NET" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.3d``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.3D```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code pour la conversion USD à STL" gistPath="" %}}
```cs
// charger le USD dans un objet de Scene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// enregistrer USD en tant que STL 
scene.Save("output.stl", Aspose.ThreeD.FileFormat.STLASCII);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}