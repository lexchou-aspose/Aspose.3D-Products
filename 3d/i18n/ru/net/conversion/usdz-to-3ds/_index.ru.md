---
title: Конвертировать USDZ в 3DS через C# 
description: Конвертируйте USDZ и другие 3D файлы с помощью .NET API
url: /ru/net/conversion/usdz-to-3ds/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: 3DS
otherformats: OBJ PDF FBX RVM GLTF DRC ASE DXF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Конвертировать USDZ в 3DS через C#" h2="Экспорт USDZ и других 3D файлов с использованием .NET Framework, .NET Core и Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Экспорт USDZ сцены как 3DS с C#" %}}
1. Загрузить файл USDZ с помощью конструктора [Сцена](https://apireference.aspose.com/3d/net/aspose.threed/scene) Класс2. Звоните [Сцена. Сохранить](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Метод
3. Передайте имя выходного файла с расширением. 3ds в качестве первого параметра
4. Укажите значение поля Discreet3DS из [Файл Формат](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Класс
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Преобразование формата API for .NET" %}}
Установите из командной строки как «nuget install Aspose.3d» или через консоль диспетчера пакетов Visual Studio с «Install-Package Aspose.3D».

Кроме того, получите автономный установщик MSI или DLL в файле ZIP из [Загрузки](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код C# для преобразования USDZ в 3DS" gistPath="" %}}
```cs
// Загрузить USDZ в объект сцены 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// Сохранить USDZ как 3DS 
scene.Save("output.3ds", Aspose.ThreeD.FileFormat.Discreet3DS);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}