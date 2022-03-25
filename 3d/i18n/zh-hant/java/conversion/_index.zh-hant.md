---
title: Java 3D 格式轉換
url: /zh-hant/java/conversion/
description: 通過 Java 庫轉換 3D 格式amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x,使用幾行 Java 代碼。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D 格式轉換通過 Java" h2="轉換 3D 文件格式,無需任何 3D 建模和渲染軟件安裝,即可構建跨平台的 Java 應用程序。" >}}

{{% blocks/products/pf/feature-page-summary %}}
對於創建、編輯、操作和保存三維圖形應用程序,**Java 3D API** 提供了高水平的方法來實現這些功能,而無需安裝任何 3D 建模和渲染軟件。 很少有人構建不同三維幾何形狀的網格,創建 3D 場景文件,在立方體上設置法線或UV,格式化元素,添加動畫屬性等等。 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="將 3D 文件轉換為不同的格式" %}}
轉換過程很簡單。 只需使用加載源 3D 文件 [場景類](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene)。 As scene是具有節點,幾何形狀,紋理,材質,動畫,姿勢,子場景等的頂級對象。 創建相關的 [保存選項](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) 例如AmfSaveOptions,ColladaSaveOptions,Discreet3dsSaveOptions,DracoSaveOptions,FbxSaveOptions,GltfSaveOptions,RvmSaveOptions,StlSaveOptions,u3dSaveOptions等,並相應地設置屬性。 最後用輸出文件調用保存方法,並創建目標格式保存選項對象。 此外,使用 API 程序員甚至可以將 3D 場景保存為 HTML。


{{% blocks/products/pf/feature-page-code h3="Java 用於 AMF 到 3DS 轉換的代碼" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="通過 Java 將 3D 場景轉換為 HTML" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}