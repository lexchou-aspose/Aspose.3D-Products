---
title: Convertir USD en GLTF via C# 
description: Convertir USD et d'autres fichiers 3D en utilisant .NET API
url: /fr/net/conversion/usd-to-gltf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: GLTF
otherformats: DRC GLTF FBX 3DS DAE RVM PDF JT 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir USD en GLTF via C#" h2="Exportez USD et d\'autres fichiers 3D à l\'aide de .NET Framework, .NET Core et Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportez USD scène comme GLTF avec C#" %}}
1. Charger le fichier USD en utilisant un constructeur de [Scène](https://apireference.aspose.com/3d/net/aspose.threed/scene) Classe2. Appel [Scène. Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Méthode
3. Passer le nom du fichier de sortie avec. Extension gltf comme premier paramètre
4. Spécifiez la valeur du champ 'GLTF' à partir de [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Classe
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D conversion de format API for .NET" %}}
Installez à partir de la ligne de commande en tant que «nuget install Aspose.3d» ou via la console du gestionnaire de packages de Visual Studio avec «Installer-Package Aspose.3D»».

Vous pouvez également obtenir l'installateur MSI hors ligne ou DLLs dans un fichier ZIP à partir de [Téléchargements](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code pour la conversion de USD à GLTF" gistPath="" %}}
```cs
// Charger le USD dans un objet de la scène 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Enregistrer USD en tant que GLTF 
scene.Save("output.gltf", Aspose.ThreeD.FileFormat.GLTF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}