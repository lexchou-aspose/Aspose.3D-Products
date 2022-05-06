---
title: Converter USDZ em PDF via C# 
description: Converta USDZ e outros 3D arquivos usando .NET API
url: /pt/net/conversion/usdz-to-pdf/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: PDF
otherformats: 3MF DRC DXF JT PLY GLTF FBX ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converter USDZ em PDF via C#" h2="Exporte USDZ e outros 3D arquivos usando .NET Framework, .NET Core e Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportar cena USDZ como PDF com C#" %}}
1. Carregue o arquivo USDZ usando um construtor de [Cena](https://apireference.aspose.com/3d/net/aspose.threed/scene) aula2. Ligue [Cena.Salvar](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) método
3. Passe o nome do arquivo de saída com extensão .pdf como primeiro parâmetro
4. Especifique o valor do campo `PDF` de [Formato de arquivo](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) aula
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Conversão de formato API for .NET" %}}
Instale a partir da linha de comando como ```nuget install Aspose.3d``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.3D```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP de [Transferências](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Código para conversão de USDZ em PDF" gistPath="" %}}
```cs
// carregue o USDZ em um objeto de Scene 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// salve USDZ como um PDF 
scene.Save("output.pdf", Aspose.ThreeD.FileFormat.PDF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}