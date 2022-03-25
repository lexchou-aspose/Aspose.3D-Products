---
title: Конвертировать USDZ в GLTF через C# 
description: Конвертируйте USDZ и другие 3D файлы с помощью .NET API
url: /ru/net/conversion/usdz-to-gltf/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: GLTF
otherformats: DRC OBJ JT DAE PDF 3MF HTML RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Конвертировать USDZ в GLTF через C#" h2="Экспорт USDZ и других 3D файлов с использованием .NET Framework, .NET Core и Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Экспорт USDZ сцены как GLTF с C#" %}}
1. Загрузить файл USDZ с помощью конструктора [Сцена](https://apireference.aspose.com/3d/net/aspose.threed/scene) Класс2. Звоните [Сцена. Сохранить](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Метод
3. Pass имя выходного файла с. Расширение gltf как первый параметр
4. Укажите значение поля GLTF из [Файл Формат](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Класс
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Преобразование формата API for .NET" %}}
Установите из командной строки как «nuget install Aspose.3d» или через консоль диспетчера пакетов Visual Studio с «Install-Package Aspose.3D».

Кроме того, получите автономный установщик MSI или DLL в файле ZIP из [Загрузки](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код C# для преобразования USDZ в GLTF" gistPath="" %}}
```cs
// Загрузить USDZ в объект сцены 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// Сохранить USDZ как GLTF 
scene.Save("output.gltf", Aspose.ThreeD.FileFormat.GLTF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}