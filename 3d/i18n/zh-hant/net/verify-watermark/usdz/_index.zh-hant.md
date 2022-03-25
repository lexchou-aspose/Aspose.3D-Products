﻿---
title: 通過 .NET 將盲水印驗證添加到 USDZ 文件格式 
weight: 830
url: /zh-hant/net/verify-watermark/usdz/ 
description: C# 源代碼加載,渲染和添加盲水印驗證到 .NET 框架,.NET 核心,Mono 上的 USDZ 文檔。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 C# 向 USDZ 添加盲水印驗證" h2="構建自己的 .NET 應用程序,使用服務器端api向 USDZ 文件添加盲水印驗證。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="USDZ" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="USDZ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 將驗證水印到 USDZ 文件" %}}

 為了給驗證 USDZ 文件加水印,我們將使用
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API 這是一個功能豐富,功能強大且易於使用的 API 平台,可用於 C# 添加任何水印驗證。 打開
 [努get](https://www.nuget.org/packages/aspose.3d) 
 包管理器,搜索
 **Aspose.3D** 
 並安裝。 您也可以使用包管理器控制台中的以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通過 C# 向 USDZ 添加盲水印驗證的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D 使開發人員只需幾行代碼就可以輕鬆地將盲水印驗證添加到 USDZ 文件中。

{{% /blocks/products/pf/agp/text %}}

- 通過場景類的構造函數加載 USDZ 文件- 獲取 Aspose.3D 的網格類- 使用 Aspose.3D 的DecodeWatermark方法添加密碼- 調用場景。 使用對象保存方法
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 所有主要操作系統都支持 Aspose.3D for .NET。 只需確保您具有以下先決條件即可。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows或具有 .NET 框架,.NET 核心,Mono 的兼容操作系統- 像微軟Visual Studio這樣的開發環境- 項目中引用的 Aspose.3D for .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# 代碼,將盲水印驗證添加到 USDZ" offSpacer="" %}}

```cs

//需要加水印以進行驗證的源文件
string file = "template.usdz";

// 創建場景實例
Scene scene = new Scene(file);
string text =null;

//通過DecodeWatermark方法添加密碼驗證水印
try
{
    scene.RootNode.Accept((Node node) =>
    {
        var mesh = node.GetEntity<Mesh>();
        if (mesh != null)
        {
            text = Watermark.DecodeWatermark(mesh, "1234");
            if (text != null)
                return false;
            }
            return true;
    });
}
catch (UnauthorizedAccessException)
{
    return "Password error";
}

//如果此文件沒有水印,則返回null; 如果有水印,則返回水印內容
return text;



```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="關於 Aspose.3D for .NET API" %}}

 Aspose.3D 是一個 CAD 和遊戲軟件 API,用於加載、修改和轉換 3D 文件。 API 是獨立的,不需要任何 3D 建模或渲染軟件。 人們可以輕鬆地將 API 用於 Discreet3DS 、 WavefrontOBJ 、 STL (ASCII,二進製) 、 Universal3D 、 FBX (ASCII,二進製) 、 Collada 、 glTF 、 PLY 、 GLB 、DirectX等多種格式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

 {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="免費App將盲水印驗證添加到 USDZ" sectionDescription="查看我們的實時演示 [水印驗證 USDZ](https://products.aspose.app/3d/verify-watermark/usdz) 有以下好處。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 不需要下載或設置任何東西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫或編譯代碼" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳 USDZ 文件,然後點擊 「水印」 按鈕" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" 如果需要,從鏈接下載 USDZ 文件" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="USDZ" readMoreLink="https://docs.fileformat.com/3d/usdz/" >}}
一個文件。 Usdz是 USD (通用場景描述) 文件格式的 ZIP 歸檔文件,其中包含並代理嵌入到歸檔文件中的其他格式的文件。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的App為格式添加盲水印驗證" subTitle="使用 C#,還可以將盲水印驗證添加到許多其他文件格式中,包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/3mf/" name="3MF" description="3D 製造格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/amf/" name="AMF" description="增材製造格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/ase/" name="ASE" description="2D動畫文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/dae/" name="DAE" description="數字資產交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/dxf/" name="DXF" description="圖紙互換格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/fbx/" name="FBX" description="3D 格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/glb/" name="GLB" description="3D 文件二進製表示" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/gltf/" name="GLTF" description="GL傳輸格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/jt/" name="JT" description="木星鑲嵌文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/obj/" name="OBJ" description="3D 文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/ply/" name="PLY" description="多邊形文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/rvm/" name="RVM" description="AVEVA工廠設計模型" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/stl/" name="STL" description="可互換的 3D 曲面幾何形狀" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/vrml/" name="VRML" description="虛擬現實建模語言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/x/" name="X" description="DirectX模型圖像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/usd/" name="USD" description="通用場景描述" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/3ds/" name="3DS" description="3D Studio網格文件格式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}