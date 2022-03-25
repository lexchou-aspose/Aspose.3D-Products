﻿---
title: Java 経由で GLTF を DAE に変換 
weight: 900
url: /ja/java/conversion/gltf-to-dae/ 
description: GLTF 形式の Java ファイルへの変換コードのサンプル。このコード例を使用して、Webまたはデスクトップ Java ベースのアプリケーション内で GLTF を DAE に変換します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java 経由で GLTF を DAE に変換" h2="3D モデリングソフトウェアなしで Java ライブラリを使用した GLTF から DAE への変換。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="DAE" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Java を使用して GLTF を DAE に変換する方法" %}}

 GLTF を DAE にレンダリングするには、を使用します。
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API は、機能が豊富でパワフルで使いやすいコンバージョン API for Java プラットフォームです。から直接最新バージョンをダウンロードできます
 [メイヴン](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 以下の設定をpom.xmlに追加して、Mavenベースのプロジェクト内にインストールします。

{{% blocks/products/pf/agp/code-block title="リポジトリ" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依存関係" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-3d</artifactId>
<version>version of aspose-3d API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Java 経由で GLTF を DAE に変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Java 人のプログラマーは、わずか数行のコードで GLTF ファイルを DAE に簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介した GLTF ファイルの読み込み1. DaeSaveOptionsのインスタンスを作成する1. 高度な変換のために DAE 固有のプロパティを設定する1. Scene.saveメソッドを呼び出す1. DaeSaveOptionsの DAE ファイル拡張子とオブジェクトで出力パスを渡す
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要件" %}}

{{% blocks/products/pf/agp/text %}}

 Java 変換コードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft WindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用の Java ランタイム環境を備えた互換性のあるOS。- 最新バージョンの Aspose.3D for Java をMavenから直接入手してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="GLTF ~ DAE Java 変換ソースコード" offSpacer="" %}}

```cs
// Sceneのオブジェクトに GLTF をロードする 
Scene document = new Scene("template.gltf");
// DaeSaveOptionsのインスタンスを作成する 
DaeSaveOptions options = new DaeSaveOptions();
// GLTF を DAE として保存 
document.save("output.dae", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="GLTF から DAE の変換ライブデモ" sectionDescription="[GLTF を DAE に変換](https://products.aspose.app/3d/conversion/gltf-to-dae) ライブデモのウェブサイトをご覧ください。ライブデモには次の利点があります" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API をダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" GLTF ファイルをアップロードするだけで、即座に DAE に変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D シーン操作ライブラリ" %}}

 Aspose.3D は CAD で、 3D ファイルをロード、変更、変換するためのゲームウェア API です。 API はスタンドアロンであり、 3D モデリングまたはレンダリングソフトウェアを必要としません。 Discreet3DS 、 WavefrontOBJ 、 STL (ASCII、Binary) 、 Universal3D 、 FBX (ASCII、Binary) 、 Collada 、 glTF 、 PLY 、 GLB 、DirectXなどのフォーマットに API を簡単に使用できます。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF (GL Transmission Format) は、 3D のモデル情報をJSON形式で格納する 3D ファイル形式です。JSONを使用すると、 3D 個のアセットのサイズと、それらのアセットの開梱および使用に必要なランタイム処理の両方が最小化されます。アプリケーションによる 3D シーンとモデルの効率的な伝送と読み込みに採用されました。 glTF はKhronos Groupによって開発された 3D フォーマットワーキンググループであり、作成者によって 3D のJPEGとも呼ばれています。この形式は、オーサリングワークフローを合理化し、業界全体でコンテンツの相互運用可能な使用を可能にする 3D コンテンツツールおよびサービスの拡張可能で一般的な公開形式を定義します。 glTF ファイル形式の作成の背後にある意図は、オーサリングワークフローを合理化し、業界全体でコンテンツの相互運用可能な使用を可能にする 3D コンテンツツールおよびサービスの拡張可能で一般的な公開形式を定義することでした。WebGLやその他のAPIを使用するアプリケーションによるランタイム処理を最小限に抑えます。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}

DAE ファイルは、インタラクティブ 3D アプリケーション間でデータを交換するために使用されるDigital Asset Exchangeファイル形式です。このファイル形式は、グラフィックソフトウェアアプリケーション間でデジタル資産を交換するためのオープンスタンダードXMLスキーマであるCOLLADA (COLLAborative Design Activity) XMLスキーマに基づいています。これは、公開されている仕様であるISO/pAS17506としてISOによって採用されています。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされる変換" subTitle="GLTF を以下のいくつかを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-3ds/" name="GLTF から 3DS" description="3D Studio DOSメッシュ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-amf/" name="GLTF から AMF" description="添加剤製造フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-ase/" name="GLTF から ASE" description="2Dアニメーションファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-fbx/" name="GLTF から FBX" description="3D フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-html/" name="GLTF から HTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-obj/" name="GLTF から OBJ" description="3D ファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-ply/" name="GLTF から PLY" description="Polygonファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-rvm/" name="GLTF から RVM" description="AVEVA植物デザインモデル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-stl/" name="GLTF から STL" description="交換可能な 3D 面ジオメトリ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-u3d/" name="GLTF から U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}