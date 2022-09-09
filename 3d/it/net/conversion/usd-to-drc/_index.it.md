---
title: Converti USD in DRC tramite C# 
description: Converti USD e altri 3D file utilizzando .NET API
url: /it/net/conversion/usd-to-drc/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: DRC
otherformats: PLY AMF DRC FBX RVM OBJ STL 3DS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converti USD in DRC tramite C#" h2="Esporta file USD e altri 3D utilizzando .NET Framework, .NET Core e Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Esporta USD scena come DRC con C#" %}}
1. Carica il file USD utilizzando un costruttore di [Scena](https://apireference.aspose.com/3d/net/aspose.threed/scene) classe2. Chiama [Scene.Salva](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) metodo
3. Passare il nome del file di output con estensione .drc come primo parametro
4. Specificare il valore del campo `Draco` da [Formato del file](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) classe
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Conversione formato API for .NET" %}}
Installa dalla riga di comando come ```nuget install Aspose.3d``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.3D```.

In alternativa, ottieni il programma di installazione MSI offline o le DLL in un file ZIP da [download](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Codice per la conversione da USD a DRC" gistPath="" %}}
```cs
// carica USD in un oggetto di Scene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// salva USD come DRC 
scene.Save("output.drc", Aspose.ThreeD.FileFormat.Draco);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}