---
title: Convert USD to FBX via C# 
description: Převést USD a další 3D soubory pomocí .NET API
url: /cs/net/conversion/usd-to-fbx/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: FBX
otherformats: PLY DRC AMF OBJ GLTF DXF PDF FBX 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert USD to FBX via C#" h2="Exportovat USD a další 3D soubory pomocí .NET framework, .NET core a Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportovat scénu USD jako FBX s C#" %}}
1. Načíst soubor USD pomocí konstruktora [Scéna](https://apireference.aspose.com/3d/net/aspose.threed/scene) Třída2. call [Scéna. uložit](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Metoda
3. pass output file name with. Rozšíření fbx jako první parametr
4. zadejte hodnotu pole fbx7700binary' od [Formát souboru](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Třída
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D formát konverzace API for .NET" %}}
Nainstalovat z příkazového řádku jako "nuget install Aspose.3d" nebo přes konzolu správce balíků visual studio s "" install-package Aspose.3D "".

Alternativně získejte offline instalační program msi nebo dll v souboru ZIP od [Stahování](https://downloads.aspose.com/3d/net)A.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# kód pro převedení USD na FBX-= = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = =" gistPath="" %}}
```cs
// Načíst USD v objektu scény 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Uložit USD jako FBX 
scene.Save("output.fbx", Aspose.ThreeD.FileFormat.FBX7700Binary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}