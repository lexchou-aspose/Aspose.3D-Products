---
title: Wandeln Sie USDZ über C# in AMF um 
description: Konvertieren Sie USDZ- und andere 3D-Dateien mit .NET API
url: /de/net/conversion/usdz-to-amf/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: AMF
otherformats: AMF DAE HTML JT PDF DRC DXF PLY 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Wandeln Sie USDZ über C# in AMF um" h2="Exportieren Sie USDZ- und andere 3D-Dateien mit .NET Framework, .NET Core und Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportiere USDZ Szene als AMF mit C#" %}}
1. Laden Sie die USDZ-Datei mit einem Konstruktor von [Szene](https://apireference.aspose.com/3d/net/aspose.threed/scene) Klasse2. Anruf [Szene.Speichern](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Methode
3. Übergeben Sie den Namen der Ausgabedatei mit der Erweiterung .amf als ersten Parameter
4. Geben Sie den Feldwert `AMF` von an [Datei Format](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Klasse
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Formatkonvertierung API for .NET" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.3d``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.3D```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei herunterladen [Downloads](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code für Umwandlung von USDZ in AMF" gistPath="" %}}
```cs
// Laden Sie die USDZ in ein Objekt der Szene 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// speichere USDZ als AMF 
scene.Save("output.amf", Aspose.ThreeD.FileFormat.AMF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}