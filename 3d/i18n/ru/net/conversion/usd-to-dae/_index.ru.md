---
title: Преобразование USD в DAE через C# 
description: Преобразуйте USD и другие 3D файлы, используя .NET API
url: /ru/net/conversion/usd-to-dae/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: DAE
otherformats: FBX OBJ DXF HTML DAE STL RVM DRC 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразование USD в DAE через C#" h2="Экспорт USD и других файлов 3D с помощью .NET Framework, .NET Core и Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Экспорт сцены USD как DAE с помощью C#" %}}
1. Загрузите файл USD с помощью конструктора [Сцена](https://apireference.aspose.com/3d/net/aspose.threed/scene) класс2. Звонок [Сцена.Сохранить](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) метод
3. Передайте имя выходного файла с расширением .dae в качестве первого параметра.
4. Укажите значение поля `Collada` из [Формат файла](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) класс
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Преобразование формата API for .NET" %}}
Установите из командной строки как ```nuget install Aspose.3d``` или через консоль диспетчера пакетов Visual Studio с ```Install-Package Aspose.3D```.

Кроме того, можно получить автономный установщик MSI или библиотеки DLL в файле ZIP из [загрузки](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код C# для преобразования USD в DAE" gistPath="" %}}
```cs
// загрузить USD в объект сцены 
var scene = new Aspose.ThreeD.Scene("template.usd");
// сохранить USD как DAE 
scene.Save("output.dae", Aspose.ThreeD.FileFormat.Collada);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}