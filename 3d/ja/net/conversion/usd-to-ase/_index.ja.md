---
title: C#を介してUSDをASEに変換します 
description: .NETAPIを使用してUSDおよびその他の3Dファイルを変換します
url: /ja/net/conversion/usd-to-ase/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: ASE
otherformats: ASE 3DS STL PLY GLTF DAE DRC HTML 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C#を介してUSDをASEに変換します" h2=".NETフレームワーク、.NETコア、およびMonoを使用してUSDおよびその他の3Dファイルをエクスポートします" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="USDシーンをC#付きのASEとしてエクスポート" %}}
1. のコンストラクタを使用してUSDファイルをロードします [シーン](https://apireference.aspose.com/3d/net/aspose.threed/scene) クラス2.電話する [Scene.Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 方法
3.最初のパラメーターとして.ase拡張子を持つ出力ファイル名を渡します
4.から`ASE`フィールド値を指定します [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) クラス
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3Dフォーマット変換APIfor .NET" %}}
コマンドラインから```nuget install Aspose.3d```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから`` `Install-PackageAspose.3D```を使用してインストールします。

または、オフラインのMSIインストーラーまたはDLLをZIPファイルから取得します。 [ダウンロード](https://releases.aspose.com/3d/net)。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C#USDからASEへの変換のコード" gistPath="" %}}
```cs
// シーンのオブジェクトにUSDをロードします 
var scene = new Aspose.ThreeD.Scene("template.usd");
// USDをASEとして保存 
scene.Save("output.ase", Aspose.ThreeD.FileFormat.ASE);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}