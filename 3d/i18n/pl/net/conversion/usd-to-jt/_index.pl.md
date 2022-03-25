---
title: Konwertuj USD na JT za pośrednictwem C# 
description: Konwertuj pliki USD i inne 3D za pomocą .NET API
url: /pl/net/conversion/usd-to-jt/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: JT
otherformats: OBJ DXF PLY PDF GLTF RVM FBX ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konwertuj USD na JT za pośrednictwem C#" h2="Eksportuj USD i inne 3D plików przy użyciu .NET Framework, .NET Core i Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Eksportuj USD sceny jako JT z C#" %}}
1. Załaduj plik USD za pomocą konstruktora [Scena](https://apireference.aspose.com/3d/net/aspose.threed/scene) Klasa2. Zadzwoń [Scena. Zapisz](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Metoda
3. Przekaż nazwę pliku wyjściowego za pomocą. Jt rozszerzenie jako pierwszy parametr
4. Określ wartość pola „ SiemensJT9 ”z [Format plików](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Klasa
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="API for .NET Konwersja formatu 3D" %}}
Zainstaluj z wiersza poleceń jako ''nuget install Aspose.3d'' lub przez konsolę Menedżera pakietów w Visual Studio z ''Zainstaluj pakiet Aspose.3D''.

Alternatywnie, pobierz instalator MSI offline lub biblioteki DLL w pliku ZIP z [Pliki do pobrania](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Kod dla USD do JT konwersji" gistPath="" %}}
```cs
// Załaduj USD w obiekcie Scene 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Zapisz USD jako JT 
scene.Save("output.jt", Aspose.ThreeD.FileFormat.SiemensJT9);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}