---
title: Převést USD na FBX prostřednictvím C# 
description: Převeďte USD a další soubory 3D pomocí .NET API
url: /cs/net/conversion/usd-to-fbx/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: FBX
otherformats: PLY DRC AMF OBJ GLTF DXF PDF FBX 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Převést USD na FBX prostřednictvím C#" h2="Exportujte USD a další soubory 3D pomocí .NET Framework, .NET Core a Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportovat scénu USD jako FBX pomocí C#" %}}
1. Načtěte soubor USD pomocí konstruktoru z [Scéna](https://apireference.aspose.com/3d/net/aspose.threed/scene) třída2. Zavolejte [Scene.Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) metoda
3. Jako první parametr předejte název výstupního souboru s příponou .fbx
4. Zadejte hodnotu pole „FBX7700Binary“ z [Formát souboru](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) třída
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Převod formátu API for .NET" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.3d``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.3D```.

Případně můžete získat offline instalační program MSI nebo knihovny DLL v souboru ZIP [stahování](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Kód pro konverzi USD na FBX" gistPath="" %}}
```cs
// načtěte USD do objektu scény 
var scene = new Aspose.ThreeD.Scene("template.usd");
// uložit USD jako FBX 
scene.Save("output.fbx", Aspose.ThreeD.FileFormat.FBX7700Binary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}