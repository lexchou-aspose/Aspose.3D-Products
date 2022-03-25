---
title: Convertire da USD a 3DS tramite C# 
description: Convertire USD e altri 3D file utilizzando .NET API
url: /it/net/conversion/usd-to-3ds/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: 3DS
otherformats: OBJ STL HTML FBX RVM JT DAE DXF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertire da USD a 3DS tramite C#" h2="Esporta USD e altri 3D file utilizzando .NET Framework, .NET Core e Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Esporta USD scena come 3DS con C#" %}}
1. Carica USD file utilizzando un costruttore di [Scena](https://apireference.aspose.com/3d/net/aspose.threed/scene) Classe2. Chiama [Scena. Salva](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Metodo
3. Passare il nome del file di output con l'estensione. 3ds come primo parametro
4. Specificare il valore del campo Discreet3DS [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Classe
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D conversione del formato API for .NET" %}}
Installa dalla riga di comando come '''nugget install Aspose.3d''' o tramite Package Manager Console di Visual Studio con '''Installa-Package Aspose.3D'''.

In alternativa, ottieni il programma di installazione o le DLL MSI offline in un file ZIP da [Download](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# codice per la conversione da USD a 3DS" gistPath="" %}}
```cs
// Caricare il USD in un oggetto di scena 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Salva USD come 3DS 
scene.Save("output.3ds", Aspose.ThreeD.FileFormat.Discreet3DS);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}