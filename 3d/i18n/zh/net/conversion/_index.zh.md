---
title: C# 3D 格式转换
url: /zh/net/conversion/
description: 通过 .NET 库转换 3D 格式3ds 3mf amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x，使用几行 C# 代码。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D 格式转换通过 C#" h2="转换 3D 文档格式，无需任何 3D 建模和渲染软件即可构建跨平台的 .NET 应用程序。" >}}

{{% blocks/products/pf/feature-page-summary %}}
开发人员可以使用 3D 图形库轻松阅读，创建，转换，更新和控制 3D 格式的内容。API 支持的格式很少有 WavefrontOBJ，Discreet3DS，STL (ASCII，二进制)，FBX (ASCII，二进制)，Universal3D，Collada，GLB，glTF，PLY，DirectX，Google Draco 格式和更多。转换过程很容易通过实例加载源文件 [场景类](https://apireference.aspose.com/3d/net/aspose.threed/scene),并使用相关的输出格式参数调用Save方法。

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 3D 场景转换为各种格式" %}}
开发人员可以通过上面列出的相同过程轻松转换 3D 场景。考虑很少的例子，例如 **FBX 到 OBJ 转换 **。通过场景类对象加载 FBX 文件。使用创建保存选项 [对象选项](https://apireference.aspose.com/3d/net/aspose.threed.formats/objsaveoptions) 并调用具有输出文件路径和obj选项作为参数的场景保存方法。API 具有适当的选项类，用于保存到相关类中，例如 [A3dwSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/a3dwsaveoptions) [AmfSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/amfsaveoptions) [离散3dssaveoptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/discreet3dssaveoptions) [FbxSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/fbxsaveoptions) [Html5保存选项](https://apireference.aspose.com/3d/net/aspose.threed.formats/html5saveoptions) [RvmSaveOptions](https://apireference.aspose.com/3d/net/aspose.threed.formats/rvmsaveoptions) 还有更多。这是 3D 的完整列表 [转换格式](https://apireference.aspose.com/3d/net/aspose.threed.formats) 选项。此外，开发人员可以轻松地将 3D 场景保存到 PDF 中。

{{% blocks/products/pf/feature-page-code h3="C# 用于 FBX 到 OBJ 转换的代码" %}}

{{< gist "aspose-com-gists" "ed8b7177c365be75c2bf8d3e668f113a" "convert-fbx-to-obj.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# 代码，用于将 3D 场景转换为 PDF" %}}

{{< gist "aspose-3d" "631532eeb21c3374f2ed" "Examples-CSharp-Loading-and-Saving-Save3DInPdf-Save3DInPdf.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}