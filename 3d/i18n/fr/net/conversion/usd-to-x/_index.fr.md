---
title: Convertir USD en X via C# 
description: Convertir USD et d'autres fichiers 3D en utilisant .NET API
url: /fr/net/conversion/usd-to-x/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: X
otherformats: PLY FBX AMF ASE 3DS JT HTML STL 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir USD en X via C#" h2="Exportez USD et d\'autres fichiers 3D à l\'aide de .NET Framework, .NET Core et Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportez USD scène comme X avec C#" %}}
1. Charger le fichier USD en utilisant un constructeur de [Scène](https://apireference.aspose.com/3d/net/aspose.threed/scene) Classe2. Appel [Scène. Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Méthode
3. Passer le nom du fichier de sortie avec. Extension x comme premier paramètre
4. Spécifiez la valeur du champ «XBinary» à partir de [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Classe
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D conversion de format API for .NET" %}}
Installez à partir de la ligne de commande en tant que «nuget install Aspose.3d» ou via la console du gestionnaire de packages de Visual Studio avec «Installer-Package Aspose.3D»».

Vous pouvez également obtenir l'installateur MSI hors ligne ou DLLs dans un fichier ZIP à partir de [Téléchargements](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code pour USD à X Conversion" gistPath="" %}}
```cs
// Charger le USD dans un objet de la scène 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Enregistrer USD en tant que X 
scene.Save("output.x", Aspose.ThreeD.FileFormat.XBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}