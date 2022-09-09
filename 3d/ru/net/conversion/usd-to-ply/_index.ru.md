---
title: Преобразование USD в PLY через C# 
description: Преобразуйте USD и другие 3D файлы, используя .NET API
url: /ru/net/conversion/usd-to-ply/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: PLY
otherformats: PLY HTML DXF ASE DRC FBX PDF JT 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразование USD в PLY через C#" h2="Экспорт USD и других файлов 3D с помощью .NET Framework, .NET Core и Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Экспорт сцены USD как PLY с помощью C#" %}}
1. Загрузите файл USD с помощью конструктора [Сцена](https://apireference.aspose.com/3d/net/aspose.threed/scene) класс2. Звонок [Сцена.Сохранить](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) метод
3. Передайте имя выходного файла с расширением .ply в качестве первого параметра.
4. Укажите значение поля `PLY` из [Формат файла](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) класс
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Преобразование формата API for .NET" %}}
Установите из командной строки как ```nuget install Aspose.3d``` или через консоль диспетчера пакетов Visual Studio с ```Install-Package Aspose.3D```.

Кроме того, можно получить автономный установщик MSI или библиотеки DLL в файле ZIP из [загрузки](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код C# для преобразования USD в PLY" gistPath="" %}}
```cs
// загрузить USD в объект сцены 
var scene = new Aspose.ThreeD.Scene("template.usd");
// сохранить USD как PLY 
scene.Save("output.ply", Aspose.ThreeD.FileFormat.PLY);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}