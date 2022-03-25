---
title: Convertire da USDZ a GLTF tramite C# 
description: Convertire USDZ e altri 3D file utilizzando .NET API
url: /it/net/conversion/usdz-to-gltf/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: GLTF
otherformats: DRC OBJ JT DAE PDF 3MF HTML RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertire da USDZ a GLTF tramite C#" h2="Esporta USDZ e altri 3D file utilizzando .NET Framework, .NET Core e Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Esporta USDZ scena come GLTF con C#" %}}
1. Carica USDZ file utilizzando un costruttore di [Scena](https://apireference.aspose.com/3d/net/aspose.threed/scene) Classe2. Chiama [Scena. Salva](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Metodo
3. Passare il nome del file di output con. Estensione gltf come primo parametro
4. Specificare il valore del campo GLTF [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Classe
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D conversione del formato API for .NET" %}}
Installa dalla riga di comando come '''nugget install Aspose.3d''' o tramite Package Manager Console di Visual Studio con '''Installa-Package Aspose.3D'''.

In alternativa, ottieni il programma di installazione o le DLL MSI offline in un file ZIP da [Download](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# codice per la conversione da USDZ a GLTF" gistPath="" %}}
```cs
// Caricare il USDZ in un oggetto di scena 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// Salva USDZ come GLTF 
scene.Save("output.gltf", Aspose.ThreeD.FileFormat.GLTF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}