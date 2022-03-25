---
title: USD PDF-re konvertálni C#-en keresztül 
description: USD és egyéb 3D fájlok konvertálása .NET API használatával
url: /hu/net/conversion/usd-to-pdf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: PDF
otherformats: RVM HTML DRC OBJ 3DS PDF FBX DAE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="USD PDF-re konvertálni C#-en keresztül" h2="USD és egyéb 3D fájlok exportálása .NET keretrendszer, .NET core és Mono használatával" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="USD jelenet exportálása PDF C#" %}}
1. USD fájl betöltése egy konstruktor segítségével [Jelenet](https://apireference.aspose.com/3d/net/aspose.threed/scene) Osztály2. call [Jelenet. mentés](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Módszer
3. adja át a kimeneti fájl nevét. Pdf kiterjesztés, mint első paraméter
4. adja meg a 'PDF' mezőértéket a [Fileformat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Osztály
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D formátum konverzió API for .NET" %}}
A parancssorból '''nuget install Aspose.3d''-ként vagy a visual studio csomagkezelő konzolján keresztül a '''install-package Aspose.3D''-vel telepítve.

Alternatív módon szerezze be az offline msi telepítőt vagy a dll-t egy ZIP fájlban a [Letöltések](https://downloads.aspose.com/3d/net)A "", a "" ", a" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "".
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# kód USD to PDF konverzióra" gistPath="" %}}
```cs
// A USD-t a jelenet objektumába tölti 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Mentés USD PDF 
scene.Save("output.pdf", Aspose.ThreeD.FileFormat.PDF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}