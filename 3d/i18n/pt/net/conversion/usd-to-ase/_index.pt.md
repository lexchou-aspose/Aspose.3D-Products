---
title: Converter USD para ASE via C# 
description: Converta USD e outros 3D arquivos usando .NET API
url: /pt/net/conversion/usd-to-ase/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: ASE
otherformats: ASE 3DS STL PLY GLTF DAE DRC HTML 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converter USD para ASE via C#" h2="Exportar USD e outros arquivos 3D usando .NET Framework, .NET Core e Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exportar USD cena como ASE com C#" %}}
1. Carregar USD arquivo usando um construtor de [Cena](https://apireference.aspose.com/3d/net/aspose.threed/scene) Classe2. Chamada [Cena. Salvar](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Método
3. Passe o nome do arquivo de saída com. Ase extensão como primeiro parâmetro
4. Especifique o valor do campo 'ASE' de [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Classe
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Conversão de Formato API for .NET" %}}
Instale a partir da linha de comando como '''nogget install Aspose.3d'' ''ou via Console do Package Manager do Visual Studio com'' 'Install-Package Aspose.3D'''.

Como alternativa, obtenha o instalador MSI offline ou DLLs em um arquivo ZIP de [Downloads](https://downloads.aspose.com/3d/net)...
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Código para USD para ASE Conversão" gistPath="" %}}
```cs
// Carregar o USD em um objeto de cena 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Salvar USD como um ASE 
scene.Save("output.ase", Aspose.ThreeD.FileFormat.ASE);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}