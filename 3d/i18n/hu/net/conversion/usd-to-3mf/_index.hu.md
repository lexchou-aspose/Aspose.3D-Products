---
title: USD 3MF-re konvertálni C#-en keresztül 
description: USD és egyéb 3D fájlok konvertálása .NET API használatával
url: /hu/net/conversion/usd-to-3mf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: 3MF
otherformats: DAE STL JT GLTF RVM DXF PDF ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="USD 3MF-re konvertálni C#-en keresztül" h2="USD és egyéb 3D fájlok exportálása .NET keretrendszer, .NET core és Mono használatával" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="USD jelenet exportálása 3MF C#" %}}
1. USD fájl betöltése egy konstruktor segítségével [Jelenet](https://apireference.aspose.com/3d/net/aspose.threed/scene) Osztály2. call [Jelenet. mentés](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Módszer
3. pass output fájl neve. 3mf kiterjesztés első paraméter
4. adja meg a 'microsoft3mf' mező értékét a [Fileformat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Osztály
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D formátum konverzió API for .NET" %}}
A parancssorból '''nuget install Aspose.3d''-ként vagy a visual studio csomagkezelő konzolján keresztül a '''install-package Aspose.3D''-vel telepítve.

Alternatív módon szerezze be az offline msi telepítőt vagy a dll-t egy ZIP fájlban a [Letöltések](https://downloads.aspose.com/3d/net)A "", a "" ", a" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "" "".
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# kód USD to 3MF konverzióra" gistPath="" %}}
```cs
// A USD-t a jelenet objektumába tölti 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Mentés USD 3MF 
scene.Save("output.3mf", Aspose.ThreeD.FileFormat.Microsoft3MF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}