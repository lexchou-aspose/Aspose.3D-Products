---
title: Wandeln Sie USD über C# in GLTF um 
description: Konvertieren Sie USD- und andere 3D-Dateien mit .NET API
url: /de/net/conversion/usd-to-gltf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: GLTF
otherformats: DRC GLTF FBX 3DS DAE RVM PDF JT 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Wandeln Sie USD über C# in GLTF um" h2="Exportieren Sie USD- und andere 3D-Dateien mit .NET Framework, .NET Core und Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportiere USD Szene als GLTF mit C#" %}}
1. Laden Sie die USD-Datei mit einem Konstruktor von [Szene](https://apireference.aspose.com/3d/net/aspose.threed/scene) Klasse2. Anruf [Szene.Speichern](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Methode
3. Übergeben Sie den Namen der Ausgabedatei mit der Erweiterung .gltf als ersten Parameter
4. Geben Sie den Feldwert `GLTF` von an [Datei Format](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Klasse
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Formatkonvertierung API for .NET" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.3d``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.3D```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei herunterladen [Downloads](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code für Umwandlung von USD in GLTF" gistPath="" %}}
```cs
// Laden Sie die USD in ein Objekt der Szene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// speichere USD als GLTF 
scene.Save("output.gltf", Aspose.ThreeD.FileFormat.GLTF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}