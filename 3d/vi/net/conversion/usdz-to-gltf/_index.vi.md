---
title: Chuyển đổi USDZ sang GLTF qua C# 
description: Chuyển đổi USDZ và các tệp 3D khác bằng cách sử dụng .NET API
url: /vi/net/conversion/usdz-to-gltf/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: GLTF
otherformats: DRC OBJ JT DAE PDF 3MF HTML RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Chuyển đổi USDZ sang GLTF qua C#" h2="Xuất các tệp USDZ và 3D khác bằng cách sử dụng .NET Framework, .NET Core và Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Xuất USDZ Cảnh dưới dạng GLTF với C#" %}}
1. Tải tệp USDZ bằng cách sử dụng hàm tạo của [Bối cảnh](https://apireference.aspose.com/3d/net/aspose.threed/scene) lớp2. Gọi [Scene.Save](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) phương pháp
3. Chuyển tên tệp đầu ra có phần mở rộng .gltf làm tham số đầu tiên
4. Chỉ định giá trị trường `GLTF` từ [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) lớp
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Chuyển đổi Định dạng API for .NET" %}}
Cài đặt từ dòng lệnh dưới dạng `` nuget install Aspose.3d '' 'hoặc qua Bảng điều khiển Trình quản lý Gói của Visual Studio với `` Gói cài đặt Aspose.3D' '.

Ngoài ra, tải trình cài đặt MSI ngoại tuyến hoặc DLL trong tệp ZIP từ [tải xuống](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# Mã cho Chuyển đổi USDZ sang GLTF" gistPath="" %}}
```cs
// tải USDZ trong một đối tượng của Scene 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// lưu USDZ dưới dạng GLTF 
scene.Save("output.gltf", Aspose.ThreeD.FileFormat.GLTF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}