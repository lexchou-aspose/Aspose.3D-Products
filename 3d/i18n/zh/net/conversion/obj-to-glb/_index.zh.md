﻿---
title: 通过 C# 将 OBJ 转换为 GLB 
url: /zh/net/conversion/obj-to-glb/ 
description: OBJ 到 GLB C# 转换的示例代码。在VB.NET，Asp.NET 或任何基于 .NET 的应用程序中使用 API 示例代码将批处理 OBJ 文件转换为 GLB。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 C# 将 OBJ 转换为 GLB" h2="将 OBJ 渲染为 GLB，无需任何 3D 建模和渲染软件。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 将 OBJ 转换为 GLB" %}}

 为了将 OBJ 转换为 GLB，我们将使用
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API 这是一个功能丰富，功能强大且易于使用的文档操作和转换 API，适用于 C# 平台。打开
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 包管理器，搜索
 Aspose.3D 
 并安装。您也可以使用包管理器控制台中的以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 C# 将 OBJ 转换为 GLB 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 程序员只需几行代码就可以轻松地将 OBJ 文件加载和转换为 GLB。

{{% /blocks/products/pf/agp/text %}}

1. 通过场景类的构造函数加载 OBJ 文件1. 创建AmfSaveOptions实例1. 为高级转换设置 GLB 特定属性1. 调用场景。保存方法1. 传递带有 GLB 文件扩展名的输出路径 & StlSaveOptions的对象1. 检查指定路径处的结果 GLB 文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 .NET 转换代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows或具有 .NET 框架，.NET 核心，Mono 的兼容操作系统。- 像微软Visual Studio这样的开发环境。- 项目中引用的 Aspose.3D for .NET DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="此示例代码显示 OBJ 到 GLB C# 的转换" offSpacer="" %}}

```cs
// 加载场景对象中的 OBJ 
var document = new Aspose.ThreeD.Scene("template.obj");
// 创建GltfSaveOptions实例 
var options = new Aspose.ThreeD.Formats.GltfSaveOptions(FileContentType.Binary);
// 将 OBJ 保存为 GLB 
document.Save("output.glb", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="免费应用程序将 OBJ 转换为 GLB" sectionDescription="查看我们的实时演示 [OBJ 到 GLB 转换](https://products.aspose.app/3d/conversion/obj-to-glb) 有以下好处。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 不需要下载或设置任何东西。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 不需要编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 OBJ 文件，然后点击 “转换” 按钮。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将立即获得结果 GLB 文件的下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 一个 3D 文件处理库，用于操作 3D 文件，而无需任何建模和渲染软件。3D API 支持 Discreet3DS 、 WavefrontOBJ 、 FBX (ASCII，二进制) 、 GLB (ASCII，二进制) 、 Universal3D 、 Collada 、 glTF 、 GLB 、 PLY 、DirectX、 Google Draco 文件格式和更多。开发人员可以轻松创建，阅读，转换，修改和控制 3D 文档格式的实质。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
OBJ 文件由 Wavefront 的高级Visualizer应用程序用于定义和存储几何对象。通过 OBJ 文件使几何数据的向后和向前传输成为可能。多边形几何像点、线、纹理顶点、面和自由形式几何 (曲线和曲面) 都由 OBJ 格式支持。这种格式不支持动画或与场景的光线和位置相关的信息。OBJ 文件通常是由 CAD (计算机辅助设计) 生成的 3D 建模过程的最终产物。存储顶点的默认顺序是逆时针的，避免显式声明面法线。尽管 OBJ 文件在注释行中声明比例信息，但尚未声明 OBJ 坐标的单位。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}
GLB 是以GL传输格式 (glTF) 保存的 3D 模型的二进制文件格式表示。有关 3D 模型的信息，例如二进制格式的节点层次结构，相机，材料，动画和网格。此二进制格式将 glTF 资产 (JSON，.bin和图像) 存储在二进制blob中。它还避免了在 glTF 的情况下发生的文件大小增加的问题。GLB 文件格式可实现紧凑的文件大小，快速加载，完整的 3D 场景表示形式以及可进一步开发的可扩展性。格式使用model/gltf-binary作为MIME类型。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}