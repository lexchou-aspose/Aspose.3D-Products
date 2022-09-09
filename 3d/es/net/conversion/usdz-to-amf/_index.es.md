---
title: Convertir USDZ a AMF a través de C# 
description: Convierta USDZ y otros 3D archivos usando .NET API
url: /es/net/conversion/usdz-to-amf/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: AMF
otherformats: AMF DAE HTML JT PDF DRC DXF PLY 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir USDZ a AMF a través de C#" h2="Exporte USDZ y otros 3D archivos usando .NET Framework, .NET Core y Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportar USDZ escena como AMF con C#" %}}
1. Cargue el archivo USDZ usando un constructor de [Escena](https://apireference.aspose.com/3d/net/aspose.threed/scene) clase2. Llamar [Escena.Guardar](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) método
3. Pase el nombre del archivo de salida con la extensión .amf como primer parámetro
4. Especifique el valor del campo `AMF` de [Formato de archivo](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) clase
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Conversión de formato API for .NET" %}}
Instale desde la línea de comandos como ```nuget install Aspose.3d``` o a través de la consola del administrador de paquetes de Visual Studio con ```Install-Package Aspose.3D```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP de [descargas](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Código para USDZ a AMF Conversión" gistPath="" %}}
```cs
// carga el USDZ en un objeto de Escena 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// guardar USDZ como AMF 
scene.Save("output.amf", Aspose.ThreeD.FileFormat.AMF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}