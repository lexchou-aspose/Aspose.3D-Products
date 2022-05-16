﻿---
title: Xem OBJ Định dạng Tệp qua .NET 
weight: 1070
url: /vi/net/viewer/obj/ 
description: C# mã nguồn để tải, kết xuất và hiển thị OBJ tài liệu trên .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="OBJ Trình xem Tệp for .NET" h2="Kết xuất tệp OBJ mà không cần bất kỳ 3D phần mềm kết xuất và mô hình hóa nào." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OBJ" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách Xem OBJ Tệp bằng C#" %}}

 Để xem tệp OBJ, chúng tôi sẽ sử dụng
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API là nền tảng API dành cho C# giàu tính năng, mạnh mẽ và dễ sử dụng, được sử dụng với bất kỳ Người xem nào. Mở
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 quản lý gói, tìm kiếm
 ** Aspose.3D ** 
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{% blocks/products/pf/agp/code-block title="Lệnh Bảng điều khiển Trình quản lý Gói" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước để Xem OBJ qua C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D giúp các nhà phát triển dễ dàng xem tệp OBJ chỉ với vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp OBJ qua hàm tạo của lớp Scene1. Tạo một phiên bản của Html5SaveOptions1. Đặt thuộc tính cho định dạng nâng cao1. Gọi phương thức Scene.Save với đối tượng của Html5SaveOptions1. Kiểm tra tệp HTML kết quả trong trình duyệt mặc định
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET được hỗ trợ trên tất cả các hệ điều hành chính. Chỉ cần đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc hệ điều hành tương thích với .NET Framework, .NET Core, Mono- Môi trường phát triển như Microsoft Visual Studio- Aspose.3D for .NET được tham chiếu trong dự án của bạn
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# mã để xem OBJ" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// tải OBJ cảnh qua một phiên bản của Cảnh
var scene = new ThreeD.Scene("template.obj");
// tạo một đối tượng của Html5SaveOptions và đặt các thuộc tính để định dạng
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // tắt lưới
    ShowGrid = false,
    // tắt giao diện người dùng
    ShowUI = false
};

// lưu 3D cảnh dưới dạng HTML5
scene.Save(output, options);
// tải kết quả HTML trong trình duyệt mặc định
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Giới thiệu về Aspose.3D for .NET API" %}}

 Aspose.3D là một CAD và Phần mềm trò chơi API để tải, sửa đổi và chuyển đổi 3D tệp. API là một phần mềm độc lập và không yêu cầu bất kỳ 3D phần mềm kết xuất hoặc mô hình hóa nào. Người ta có thể dễ dàng sử dụng API cho Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX và các định dạng khác. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ứng dụng miễn phí để xem OBJ" sectionDescription="Kiểm tra các bản trình diễn trực tiếp của chúng tôi để [Xem OBJ](https://products.aspose.app/3d/viewer/obj) với những lợi ích sau đây." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống hoặc thiết lập bất cứ thứ gì" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần viết hoặc biên dịch mã" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải tệp OBJ lên và nhấn nút \"Xem\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Tải xuống tệp OBJ từ liên kết, nếu cần" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
OBJ tệp được ứng dụng Trình hiển thị nâng cao của Wavefront sử dụng để xác định và lưu trữ các đối tượng hình học. Việc truyền dữ liệu hình học qua lại và chuyển tiếp được thực hiện thông qua các tệp OBJ. Cả hình học đa giác như điểm, đường thẳng, đỉnh kết cấu, mặt và hình học dạng tự do (đường cong và bề mặt) đều được định dạng OBJ hỗ trợ. Định dạng này không hỗ trợ hoạt ảnh hoặc thông tin liên quan đến ánh sáng và vị trí của cảnh. Tệp OBJ thường là sản phẩm cuối cùng của quá trình tạo mô hình 3D được tạo bởi CAD (Thiết kế có sự hỗ trợ của Máy tính). Thứ tự mặc định để lưu trữ các đỉnh là ngược chiều kim đồng hồ để tránh khai báo rõ ràng các chuẩn mặt. Mặc dù tệp OBJ khai báo thông tin tỷ lệ trong một dòng nhận xét nhưng không có đơn vị nào được khai báo cho tọa độ OBJ.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các định dạng trình xem được hỗ trợ khác" subTitle="Sử dụng C#, Người ta cũng có thể xem nhiều định dạng tệp khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Lưới Studio DOS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D Định dạng Sản xuất" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="Định dạng sản xuất phụ gia" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="Tệp hoạt hình 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="Trao đổi tài sản kỹ thuật số" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="Vẽ định dạng trao đổi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D Định dạng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D Biểu diễn tệp nhị phân" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="Định dạng truyền dẫn GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="Tệp sao Mộc Tessellation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="Định dạng tệp đa giác" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="Mô hình thiết kế nhà máy AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="Hình học bề mặt 3D có thể hoán đổi cho nhau" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="Ngôn ngữ tạo mô hình thực tế ảo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="X" description="Hình ảnh mô hình DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP Định dạng Lưu trữ" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}