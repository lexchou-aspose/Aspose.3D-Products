---
title: Convertir USD a JT a través de C# 
description: Convertir USD y otros 3D archivos usando .NET API
url: /es/net/conversion/usd-to-jt/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: JT
otherformats: OBJ DXF PLY PDF GLTF RVM FBX ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir USD a JT a través de C#" h2="Exportar USD y otros 3D archivos usando .NET Framework, .NET Core y Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportar USD escena como JT con C#" %}}
1. Cargar USD archivo con un constructor de [Escena](https://apireference.aspose.com/3d/net/aspose.threed/scene) Clase2. Llamada [Escena. Guardar](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Método
3. Pase el nombre del archivo de salida con. Jt extensión como primer parámetro
4. Especifique el valor del campo 'SiemensJT9' a partir de [Formato de archivo](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Clase
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Conversión de formato API for .NET" %}}
Instale desde la línea de comandos como ''nuget install Aspose.3d'' o a través de la consola de Package Manager de Visual Studio con '''Install-Package Aspose.3D'' '.

Alternativamente, obtenga el instalador MSI o DLL sin conexión en un archivo de ZIP desde [Descargas](https://downloads.aspose.com/3d/net)...
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# código para la conversión de USD a JT" gistPath="" %}}
```cs
// Cargar el USD en un objeto de Escena 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Guardar USD como JT 
scene.Save("output.jt", Aspose.ThreeD.FileFormat.SiemensJT9);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}