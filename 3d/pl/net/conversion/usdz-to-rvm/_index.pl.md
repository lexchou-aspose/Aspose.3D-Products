---
title: Konwertuj USDZ na RVM przez C# 
description: Konwertuj pliki USDZ i inne 3D za pomocą .NET API
url: /pl/net/conversion/usdz-to-rvm/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: RVM
otherformats: DRC ASE 3MF AMF GLTF OBJ DXF RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konwertuj USDZ na RVM przez C#" h2="Eksportuj USDZ i inne 3D pliki za pomocą .NET Framework, .NET Core i Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Eksportuj USDZ scenę jako RVM z C#" %}}
1. Załaduj plik USDZ za pomocą konstruktora [Scena](https://apireference.aspose.com/3d/net/aspose.threed/scene) klasa2. Zadzwoń [Scena.Zapisz](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) metoda
3. Przekaż nazwę pliku wyjściowego z rozszerzeniem .rvm jako pierwszy parametr
4. Określ wartość pola `RvmBinary` z [Format pliku](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) klasa
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Konwersja formatu API for .NET" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.3d``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.3D```.

Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [pliki do pobrania](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Kod konwersji USDZ na RVM" gistPath="" %}}
```cs
// załaduj USDZ do obiektu sceny 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// zapisz USDZ jako RVM 
scene.Save("output.rvm", Aspose.ThreeD.FileFormat.RvmBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}