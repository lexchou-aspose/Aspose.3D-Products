---
title: 通过 C# 将 USD 转换为X 
description: 使用 .NET API 转换 USD 和其他 3D 文件
url: /zh/net/conversion/usd-to-x/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: X
otherformats: PLY FBX AMF ASE 3DS JT HTML STL 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="通过 C# 将 USD 转换为X" h2="使用 .NET 框架、 .NET 核心和 Mono 导出 USD 和其他 3D 文件" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="将 USD 场景导出为带有 C# 的X" %}}
1. 使用以下构造函数加载 USD 文件 [场景](https://apireference.aspose.com/3d/net/aspose.threed/scene) 类2.打电话 [场景。保存](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 方法
3.传递输出文件名与x扩展作为第一个参数
4.从指定 'XBinary' 字段值 [文件格式](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) 类
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D 格式转换 API for .NET" %}}
从命令行以 “'nuget Install Aspose.3d” 的身份安装，或通过Visual Studio的软件包管理器控制台安装，并带有 “” install-Package Aspose.3D ”。

或者，从 ZIP 文件中获取离线MSI安装程序或dll [下载](https://downloads.aspose.com/3d/net)。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="USD 到X转换的 C# 代码" gistPath="" %}}
```cs
// 加载场景对象中的 USD 
var scene = new Aspose.ThreeD.Scene("template.usd");
// 将 USD 保存为X 
scene.Save("output.x", Aspose.ThreeD.FileFormat.XBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}