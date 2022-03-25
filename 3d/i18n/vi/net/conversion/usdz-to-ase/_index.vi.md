---
title: Chuyển đổi USDZ để ASE qua C# 
description: Chuyển đổi USDZ & khác 3D các tập tin sử dụng .NET API
url: /vi/net/conversion/usdz-to-ase/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: ASE
otherformats: PDF 3MF GLTF DRC DXF OBJ FBX DAE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Chuyển đổi USDZ để ASE qua C#" h2="Xuất khẩu USDZ & khác 3D các tập tin sử dụng .NET Khuôn Khổ, .NET lõi và Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Xuất khẩu USDZ Cảnh như ASE với C#" %}}
1. Tải USDZ tập tin bằng cách sử dụng một Constructor của [Cảnh](https://apireference.aspose.com/3d/net/aspose.threed/scene) Lớp2. cuộc gọi [Cảnh. Tiết Kiệm](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Phương pháp
3. vượt qua đầu ra Tên tập tin với. Ase mở rộng đầu tiên Thông số
4. xác định 'ASE' lĩnh vực giá trị từ [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Lớp
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Chuyển Đổi định dạng API for .NET" %}}
Cài đặt từ dòng lệnh như '''nuget cài đặt Aspose.3d'' 'hoặc thông qua Gói Quản Lý Giao Diện Điều Khiển của Hình Ảnh Phòng Thu với '''Install-Gói Aspose.3D' ''.

Ngoài ra, có được các ẩn MSI cài đặt hoặc DLL trong một ZIP tập tin từ [Tải](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# mã cho USDZ để ASE Chuyển Đổi" gistPath="" %}}
```cs
// Tải các USDZ trong một đối tượng của Cảnh 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// Tiết kiệm USDZ như một ASE 
scene.Save("output.ase", Aspose.ThreeD.FileFormat.ASE);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}