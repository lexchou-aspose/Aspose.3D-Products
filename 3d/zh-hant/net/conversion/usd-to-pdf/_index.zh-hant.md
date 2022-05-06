---
title: 通過 C# 將 USD 轉換為 PDF 
description: 使用 .NET API 轉換 USD 和其他 3D 文件
url: /zh-hant/net/conversion/usd-to-pdf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: PDF
otherformats: RVM HTML DRC OBJ 3DS PDF FBX DAE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="通過 C# 將 USD 轉換為 PDF" h2="使用 .NET Framework、.NET Core 和 Mono 導出 USD 和其他 3D 文件" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="使用 C# 將 USD 場景導出為 PDF" %}}
1. 使用構造函數加載 USD 文件 [場景](https://apireference.aspose.com/3d/net/aspose.threed/scene) 班級2. 打電話 [場景.保存](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 方法
3. 將帶有 .pdf 擴展名的輸出文件名作為第一個參數傳遞
4. 指定 `PDF` 字段值 [文件格式](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) 班級
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D 格式轉換API for .NET" %}}
從命令行安裝為 ```nuget install Aspose.3d``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.3D``` 安裝。

或者，從 ZIP 文件中獲取脫機 MSI 安裝程序或 DLL [下載](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# USD 到 PDF 轉換的代碼" gistPath="" %}}
```cs
// 在 Scene 對像中加載 USD 
var scene = new Aspose.ThreeD.Scene("template.usd");
// 將 USD 保存為 PDF 
scene.Save("output.pdf", Aspose.ThreeD.FileFormat.PDF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}