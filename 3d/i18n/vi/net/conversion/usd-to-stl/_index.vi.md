---
title: Chuyển đổi USD để STL qua C# 
description: Chuyển đổi USD & khác 3D các tập tin sử dụng .NET API
url: /vi/net/conversion/usd-to-stl/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: STL
otherformats: OBJ DXF DAE DRC RVM STL ASE FBX 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Chuyển đổi USD để STL qua C#" h2="Xuất khẩu USD & khác 3D các tập tin sử dụng .NET Khuôn Khổ, .NET lõi và Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Xuất khẩu USD Cảnh như STL với C#" %}}
1. Tải USD tập tin bằng cách sử dụng một Constructor của [Cảnh](https://apireference.aspose.com/3d/net/aspose.threed/scene) Lớp2. cuộc gọi [Cảnh. Tiết Kiệm](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Phương pháp
3. vượt qua đầu ra Tên tập tin với. STL mở rộng đầu tiên Thông số
4. xác định 'STLASCII' lĩnh vực giá trị từ [FileFormat](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Lớp
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Chuyển Đổi định dạng API for .NET" %}}
Cài đặt từ dòng lệnh như '''nuget cài đặt Aspose.3d'' 'hoặc thông qua Gói Quản Lý Giao Diện Điều Khiển của Hình Ảnh Phòng Thu với '''Install-Gói Aspose.3D' ''.

Ngoài ra, có được các ẩn MSI cài đặt hoặc DLL trong một ZIP tập tin từ [Tải](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# mã cho USD để STL Chuyển Đổi" gistPath="" %}}
```cs
// Tải các USD trong một đối tượng của Cảnh 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Tiết kiệm USD như một STL 
scene.Save("output.stl", Aspose.ThreeD.FileFormat.STLASCII);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}