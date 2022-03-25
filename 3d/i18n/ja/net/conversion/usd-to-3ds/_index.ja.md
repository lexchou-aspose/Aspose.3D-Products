---
title: C# 経由で USD を 3DS に変換 
description: .NET API を使用して USD およびその他の 3D ファイルを変換します
url: /ja/net/conversion/usd-to-3ds/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: 3DS
otherformats: OBJ STL HTML FBX RVM JT DAE DXF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C# 経由で USD を 3DS に変換" h2=".NET Framework、 .NET Core、 Mono を使用して USD およびその他の 3D ファイルをエクスポート" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="USD シーンを 3DS として C# でエクスポート" %}}
1. のコンストラクタを使用して USD ファイルをロード [シーン](https://apireference.aspose.com/3d/net/aspose.threed/scene) クラス2.コール [シーン保存](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) メソッド
3.出力ファイル名を.3ds拡張子で最初のパラメータとして渡す
4.から「 Discreet3DS 」フィールド値を指定します。 [ファイル形式](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) クラス
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D フォーマット変換 API for .NET" %}}
コマンドラインから「nuget install Aspose.3d 」として、またはVisual StudioのPackage Manager Consoleから「Install-Package Aspose.3D 」でインストールします。

または、オフラインのMSIインストーラまたはDLLを ZIP ファイルから取得します。 [ダウンロード](https://downloads.aspose.com/3d/net)を使用します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="USD から 3DS の変換のための C# コード" gistPath="" %}}
```cs
// Sceneのオブジェクトに USD をロードする 
var scene = new Aspose.ThreeD.Scene("template.usd");
// USD を 3DS として保存 
scene.Save("output.3ds", Aspose.ThreeD.FileFormat.Discreet3DS);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}