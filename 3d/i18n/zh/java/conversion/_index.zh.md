---
title: Java 3D 格式转换
url: /zh/java/conversion/
description: 通过 Java 库转换 3D 格式amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x，只需几行 Java 代码。
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D 格式转换通过 Java" h2="转换 3D 文件格式，无需任何 3D 建模和渲染软件安装，即可构建跨平台的 Java 应用程序。" >}}

{{% blocks/products/pf/feature-page-summary %}}
对于创建、编辑、操作和保存三维图形应用程序，**Java 3D API** 提供了高水平的方法来实现这些功能，而无需安装任何 3D 建模和渲染软件。很少有人构建不同三维几何形状的网格，创建 3D 场景文件，在立方体上设置法线或UV，格式化元素，添加动画属性等等。 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="将 3D 文件转换为不同的格式" %}}
转换过程很简单。只需使用加载源 3D 文件 [场景类](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene)。As scene是具有节点，几何形状，纹理，材质，动画，姿势，子场景等的顶级对象。创建相关的 [保存选项](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) 例如AmfSaveOptions，ColladaSaveOptions，Discreet3dsSaveOptions，DracoSaveOptions，FbxSaveOptions，GltfSaveOptions，RvmSaveOptions，StlSaveOptions，U3dSaveOptions等，并相应地设置属性。最后用输出文件调用保存方法，并创建目标格式保存选项对象。此外，使用 API 程序员甚至可以将 3D 场景保存为 HTML。


{{% blocks/products/pf/feature-page-code h3="Java 用于 AMF 到 3DS 转换的代码" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="通过 Java 将 3D 场景转换为 HTML" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}