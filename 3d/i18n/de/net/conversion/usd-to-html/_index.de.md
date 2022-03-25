---
title: USD in HTML konvertieren über C# 
description: USD & andere 3D-Dateien mit .NET API konvertieren
url: /de/net/conversion/usd-to-html/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: HTML
otherformats: PLY PDF RVM JT ASE DXF DAE FBX 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="USD in HTML konvertieren über C#" h2="Exportieren Sie USD & andere 3D-Dateien mit .NET Framework, .NET Core und Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="USD Szene als HTML mit C# exportieren" %}}
1. Laden Sie die USD-Datei mit einem Konstruktor von [Szene](https://apireference.aspose.com/3d/net/aspose.threed/scene) Klasse2. Anruf [Szene. Speichern](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Methode
3. Geben Sie den Namen der Ausgabe datei mit. HTML-Erweiterung als erster Parameter
4. Geben Sie den Feldwert 'HTML5' aus [Format](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Klasse
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Format konvertierung API for .NET" %}}
Installieren Sie von der Befehlszeile als '''nuget install Aspose.3d'' oder über die Package Manager-Konsole von Visual Studio mit ''Install-Package Aspose.3D''.

Alternativ können Sie das Offline-MSI-Installation programm oder die DLLs in einer ZIP-Datei von [Downloads](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Code für USD in HTML Konvertierung" gistPath="" %}}
```cs
// Laden Sie die USD in einem Objekt der Szene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// USD als HTML speichern 
scene.Save("output.html", Aspose.ThreeD.FileFormat.HTML5);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}