---
title: C#を介してUSDを3MFに変換します 
description: .NETAPIを使用してUSDおよびその他の3Dファイルを変換します
url: /ja/net/conversion/usd-to-3mf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: 3MF
otherformats: DAE STL JT GLTF RVM DXF PDF ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C#を介してUSDを3MFに変換します" h2=".NETフレームワーク、.NETコア、およびMonoを使用してUSDおよびその他の3Dファイルをエクスポートします" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="USDシーンをC#付きの3MFとしてエクスポート" %}}
1. のコンストラクタを使用してUSDファイルをロードします [シーン](https://apireference.aspose.com/3d/net/aspose.threed/scene) クラス2.電話する [Scene.Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 方法
3.最初のパラメーターとして.3mf拡張子の出力ファイル名を渡します
4.から`Microsoft3MF`フィールド値を指定します [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) クラス
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3Dフォーマット変換APIfor .NET" %}}
コマンドラインから```nuget install Aspose.3d```としてインストールするか、VisualStudioのパッケージマネージャーコンソールから`` `Install-PackageAspose.3D```を使用してインストールします。

または、オフラインのMSIインストーラーまたはDLLをZIPファイルから取得します。 [ダウンロード](https://downloads.aspose.com/3d/net)。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C#USDから3MFへの変換のコード" gistPath="" %}}
```cs
// シーンのオブジェクトにUSDをロードします 
var scene = new Aspose.ThreeD.Scene("template.usd");
// USDを3MFとして保存 
scene.Save("output.3mf", Aspose.ThreeD.FileFormat.Microsoft3MF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}