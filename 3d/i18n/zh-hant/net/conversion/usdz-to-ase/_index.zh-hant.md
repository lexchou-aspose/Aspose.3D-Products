---
title: 通過 C# 將 USDZ 轉換為 ASE 
description: 使用 .NET API 轉換 USDZ 和其他 3D 文件
url: /zh-hant/net/conversion/usdz-to-ase/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: ASE
otherformats: PDF 3MF GLTF DRC DXF OBJ FBX DAE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="通過 C# 將 USDZ 轉換為 ASE" h2="使用 .NET 框架、 .NET 核心和 Mono 導出 USDZ 和其他 3D 文件" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="使用 C# 將 USDZ 場景導出為 ASE" %}}
1. 使用以下構造函數加載 USDZ 文件 [場景](https://apireference.aspose.com/3d/net/aspose.threed/scene) 類2.打電話 [場景。 保存](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 方法
3.傳遞輸出文件名與ase擴展作為第一個參數
4.從中指定 "ASE」 字段值 [文件格式](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) 類
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D 格式轉換 API for .NET" %}}
從命令行以 「'nuget Install Aspose.3d」 的身份安裝,或通過Visual Studio的軟件包管理器控制台安裝,並帶有 「」 install-Package Aspose.3D ”。

或者,從 ZIP 文件中獲取離線MSI安裝程序或dll [下載](https://downloads.aspose.com/3d/net)。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# 用於 USDZ 到 ASE 轉換的代碼" gistPath="" %}}
```cs
// 加載場景對象中的 USDZ 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// 將 USDZ 保存為 ASE 
scene.Save("output.ase", Aspose.ThreeD.FileFormat.ASE);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}