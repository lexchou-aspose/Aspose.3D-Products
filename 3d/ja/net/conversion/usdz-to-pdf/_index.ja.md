---
title: C#を介してUSDZをPDFに変換します 
description: .NETAPIを使用してUSDZおよびその他の3Dファイルを変換します
url: /ja/net/conversion/usdz-to-pdf/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: PDF
otherformats: 3MF DRC DXF JT PLY GLTF FBX ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C#を介してUSDZをPDFに変換します" h2=".NETフレームワーク、.NETコア、およびMonoを使用してUSDZおよびその他の3Dファイルをエクスポートします" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="USDZシーンをC#付きのPDFとしてエクスポート" %}}
1. のコンストラクタを使用してUSDZファイルをロードします [シーン](https://apireference.aspose.com/3d/net/aspose.threed/scene) クラス2.電話する [Scene.Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 方法
3.最初のパラメーターとして.pdf拡張子を持つ出力ファイル名を渡します
4.から`PDF`フィールド値を指定します [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) クラス
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3Dフォーマット変換APIfor .NET" %}}
コマンドラインから```nuget install Aspose.3d```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから`` `Install-PackageAspose.3D```を使用してインストールします。

または、オフラインのMSIインストーラーまたはDLLをZIPファイルから取得します。 [ダウンロード](https://releases.aspose.com/3d/net)。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C#USDZからPDFへの変換のコード" gistPath="" %}}
```cs
// シーンのオブジェクトにUSDZをロードします 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// USDZをPDFとして保存 
scene.Save("output.pdf", Aspose.ThreeD.FileFormat.PDF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}