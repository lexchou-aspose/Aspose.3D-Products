---
title: 通過 C# 將 USDZ 轉換為 RVM 
description: 使用 .NET API 轉換 USDZ 和其他 3D 文件
url: /zh-hant/net/conversion/usdz-to-rvm/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: RVM
otherformats: DRC ASE 3MF AMF GLTF OBJ DXF RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="通過 C# 將 USDZ 轉換為 RVM" h2="使用 .NET Framework、.NET Core 和 Mono 導出 USDZ 和其他 3D 文件" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="使用 C# 將 USDZ 場景導出為 RVM" %}}
1. 使用構造函數加載 USDZ 文件 [場景](https://apireference.aspose.com/3d/net/aspose.threed/scene) 班級2. 打電話 [場景.保存](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 方法
3. 將帶有 .rvm 擴展名的輸出文件名作為第一個參數傳遞
4. 指定 `RvmBinary` 字段值 [文件格式](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) 班級
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D 格式轉換API for .NET" %}}
從命令行安裝為 ```nuget install Aspose.3d``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.3D``` 安裝。

或者，從 ZIP 文件中獲取脫機 MSI 安裝程序或 DLL [下載](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# USDZ 到 RVM 轉換的代碼" gistPath="" %}}
```cs
// 在 Scene 對像中加載 USDZ 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// 將 USDZ 保存為 RVM 
scene.Save("output.rvm", Aspose.ThreeD.FileFormat.RvmBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}