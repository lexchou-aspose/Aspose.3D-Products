---
title: Konwertuj USDZ na DAE przez C# 
description: Konwertuj pliki USDZ i inne 3D za pomocą .NET API
url: /pl/net/conversion/usdz-to-dae/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: DAE
otherformats: DRC HTML DAE ASE STL PLY 3MF OBJ 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konwertuj USDZ na DAE przez C#" h2="Eksportuj USDZ i inne 3D pliki za pomocą .NET Framework, .NET Core i Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Eksportuj USDZ scenę jako DAE z C#" %}}
1. Załaduj plik USDZ za pomocą konstruktora [Scena](https://apireference.aspose.com/3d/net/aspose.threed/scene) klasa2. Zadzwoń [Scena.Zapisz](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) metoda
3. Przekaż nazwę pliku wyjściowego z rozszerzeniem .dae jako pierwszy parametr
4. Określ `Collada` wartość pola z [Format pliku](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) klasa
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Konwersja formatu API for .NET" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.3d``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.3D```.

Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [pliki do pobrania](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Kod konwersji USDZ na DAE" gistPath="" %}}
```cs
// załaduj USDZ do obiektu sceny 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// zapisz USDZ jako DAE 
scene.Save("output.dae", Aspose.ThreeD.FileFormat.Collada);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}