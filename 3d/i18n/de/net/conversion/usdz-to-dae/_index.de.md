---
title: USDZ in DAE konvertieren über C# 
description: USDZ & andere 3D-Dateien mit .NET API konvertieren
url: /de/net/conversion/usdz-to-dae/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: DAE
otherformats: DRC HTML DAE ASE STL PLY 3MF OBJ 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="USDZ in DAE konvertieren über C#" h2="Exportieren Sie USDZ & andere 3D-Dateien mit .NET Framework, .NET Core und Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="USDZ Szene als DAE mit C# exportieren" %}}
1. Laden Sie die USDZ-Datei mit einem Konstruktor von [Szene](https://apireference.aspose.com/3d/net/aspose.threed/scene) Klasse2. Anruf [Szene. Speichern](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Methode
3. Geben Sie den Namen der Ausgabe datei mit. Dae-Erweiterung als erster Parameter
4. Geben Sie den Feldwert 'Collada' aus [Format](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Klasse
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Format konvertierung API for .NET" %}}
Installieren Sie von der Befehlszeile als '''nuget install Aspose.3d'' oder über die Package Manager-Konsole von Visual Studio mit ''Install-Package Aspose.3D''.

Alternativ können Sie das Offline-MSI-Installation programm oder die DLLs in einer ZIP-Datei von [Downloads](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code für USDZ in DAE Konvertierung" gistPath="" %}}
```cs
// Laden Sie die USDZ in einem Objekt der Szene 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// USDZ als DAE speichern 
scene.Save("output.dae", Aspose.ThreeD.FileFormat.Collada);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}