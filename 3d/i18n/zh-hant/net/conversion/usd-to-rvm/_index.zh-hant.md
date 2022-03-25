---
title: 通過 C# 將 USD 轉換為 RVM 
description: 使用 .NET API 轉換 USD 和其他 3D 文件
url: /zh-hant/net/conversion/usd-to-rvm/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: RVM
otherformats: STL HTML DAE ASE FBX PLY GLTF PDF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="通過 C# 將 USD 轉換為 RVM" h2="使用 .NET 框架、 .NET 核心和 Mono 導出 USD 和其他 3D 文件" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="使用 C# 將 USD 場景導出為 RVM" %}}
1. 使用以下構造函數加載 USD 文件 [場景](https://apireference.aspose.com/3d/net/aspose.threed/scene) 類2.打電話 [場景。 保存](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 方法
3.傳遞輸出文件名與rvm擴展作為第一個參數
4.從指定 'RvmBinary' 字段值 [文件格式](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) 類
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D 格式轉換 API for .NET" %}}
從命令行以 「'nuget Install Aspose.3d」 的身份安裝,或通過Visual Studio的軟件包管理器控制台安裝,並帶有 「」 install-Package Aspose.3D ”。

或者,從 ZIP 文件中獲取離線MSI安裝程序或dll [下載](https://downloads.aspose.com/3d/net)。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# 用於 USD 到 RVM 轉換的代碼" gistPath="" %}}
```cs
// 加載場景對象中的 USD 
var scene = new Aspose.ThreeD.Scene("template.usd");
// 將 USD 保存為 RVM 
scene.Save("output.rvm", Aspose.ThreeD.FileFormat.RvmBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}