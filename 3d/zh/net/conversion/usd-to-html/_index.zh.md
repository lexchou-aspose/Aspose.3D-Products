---
title: 通过 C# 将 USD 转换为 HTML 
description: 使用 .NET API 转换 USD 和其他 3D 文件
url: /zh/net/conversion/usd-to-html/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: HTML
otherformats: PLY PDF RVM JT ASE DXF DAE FBX 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="通过 C# 将 USD 转换为 HTML" h2="使用 .NET Framework、.NET Core 和 Mono 导出 USD 和其他 3D 文件" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="使用 C# 将 USD 场景导出为 HTML" %}}
1. 使用构造函数加载 USD 文件 [场景](https://apireference.aspose.com/3d/net/aspose.threed/scene) 班级2. 打电话 [场景.保存](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 方法
3. 传递带有 .html 扩展名的输出文件名作为第一个参数
4. 指定 `HTML5` 字段值 [文件格式](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) 班级
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D 格式转换API for .NET" %}}
从命令行安装为 ```nuget install Aspose.3d``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.3D``` 安装。

或者，从 ZIP 文件中获取脱机 MSI 安装程序或 DLL [下载](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# USD 到 HTML 转换的代码" gistPath="" %}}
```cs
// 在 Scene 对象中加载 USD 
var scene = new Aspose.ThreeD.Scene("template.usd");
// 将 USD 保存为 HTML 
scene.Save("output.html", Aspose.ThreeD.FileFormat.HTML5);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}