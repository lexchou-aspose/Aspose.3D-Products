﻿---
title: Tạo ra Đám Mây Điểm để GLB Các Định Dạng Tập Tin thông qua .NET 
weight: 830
url: /vi/net/point-cloud/glb/ 
description: C# mã nguồn để tải, làm cho và thêm tạo ra đám mây điểm để GLB tài liệu trên .NET Khuôn Khổ, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Tạo ra Đám Mây Điểm để GLB qua C#" h2="Xây dựng riêng của bạn .NET ứng dụng để tạo ra đám mây điểm để GLB các tập tin sử dụng máy chủ-Side API." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Làm thế nào để Tạo Ra Đám Mây Điểm để GLB Tập Tin Sử Dụng C#" %}}

 Trong đặt hàng để tạo ra đám mây điểm để GLB tập tin, chúng tôi sẽ sử dụng
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API mà là một tính năng phong phú, mạnh mẽ và dễ dàng để sử dụng API cho C# nền tảng để được sử dụng với tạo ra đám mây điểm. Mở
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Gói Quản Lý, tìm kiếm cho
 **Aspose.3D** 
 Và cài đặt. Bạn cũng có thể sử dụng sau đây lệnh từ các Gói Quản Lý Giao Diện Điều Khiển.

{{% blocks/products/pf/agp/code-block title="Gói Quản Lý Giao Diện Điều Khiển Lệnh" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Bước để Tạo Ra Đám Mây Điểm để GLB qua C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D làm cho nó dễ dàng cho các nhà phát triển để tạo ra đám mây điểm để các GLB tập tin với chỉ cần vài dòng của mã.

{{% /blocks/products/pf/agp/text %}}

- Tải GLB tập tin thông qua các Constructor của Cảnh lớp- Nhận được pointcloud đối tượng của Aspose.3D- Tạo ra một chuyển đổi đối tượng thông qua các EvaluateGlobalTransform phương pháp- Tạo ra đám mây điểm sử dụng Hợp Nhất phương pháp- Cuộc gọi các Cảnh. Tiết Kiệm phương pháp với đối tượng
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Yêu Cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET được hỗ trợ trên tất cả các hệ điều hành. Chỉ cần làm cho chắc chắn rằng bạn có những điều sau đây điều kiện tiên quyết.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Cửa Sổ hoặc một tương thích HỆ ĐIỀU HÀNH với .NET Khuôn Khổ, .NET Core, Mono- Môi trường phát triển giống như Microsoft Visual Studio- Aspose.3D for .NET tham chiếu trong dự án của bạn
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# mã để Tạo Ra Đám Mây Điểm để GLB" offSpacer="" %}}

```cs

//Các tập tin nguồn mà cần phải để tạo ra các đám mây điểm
string file = "template.glb";

// Tạo ra một ví dụ của Cảnh
Scene scene = new Scene(file);

//Nhận được pointcloud đối tượng của Aspose.3D và tạo ra một đám mây điểm
var pc = new PointCloud();
scene.RootNode.Accept((Node n) =>
{
    if (n.Entities.Count > 0)
    {
        var transform = n.EvaluateGlobalTransform(true);
        foreach (var entity in n.Entities)
        {
            if (entity is Geometry g)
            {
                Merge(pc, g, transform);
            }
            else if (entity is IMeshConvertible mc)
            {
                var mesh = mc.ToMesh();
                Merge(pc, mesh, transform);
            }

        }
    }
    return true;
});

//Hợp nhất phương pháp cho tạo ra điểm Những đám mây
private void Merge(PointCloud pc, Geometry g, Matrix4 transform)
{
    var tmp = PointCloud.FromGeometry(g, 10);
    for (int i = 0; i < tmp.ControlPoints.Count; i++)
    {
        var pt = transform * tmp.ControlPoints[i];
        pc.ControlPoints.Add(pt);
    }
}

// Tạo ra một ví dụ của newScene
var newScene = new Scene(pc);

//Khi tiết kiệm, bạn cần phải để tạo ra một SaveOptions đối tượng của các tiết kiệm định dạng
string output=System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".ply";
PlySaveOptions ply = new PlySaveOptions();
ply.PointCloud = true;
newScene.Save(output,ply);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Khoảng Aspose.3D for .NET API" %}}

 Aspose.3D là một CAD và Gameware API để tải, sửa đổi và chuyển đổi 3D các tập tin. API là một độc lập và không yêu cầu bất kỳ bất kỳ 3D mô hình hoặc vẽ phần mềm. Một có thể dễ dàng sử dụng API cho Discreet3DS, WavefrontOBJ, STL (ASCII, Nhị Phân), Universal3D, FBX (ASCII, nhị phân), Collada, glTF, PLY, GLB, directX và nhiều hơn nữa các định dạng. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ứng Dụng miễn phí để Tạo Ra Đám Mây Điểm để GLB" sectionDescription="Kiểm tra trực tiếp của chúng tôi trình diễn để [Đám Mây điểm 3DS](https://products.aspose.app/3d/point-cloud/glb) Với lợi ích sau đây." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần phải tải về hoặc tải thiết lập bất cứ điều gì" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không có cần phải viết hoặc biên dịch mã" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên GLB tập tin và nhấn \"Tạo Ra\" nút" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Tải về GLB tập tin từ các liên kết, nếu có yêu cầu" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}
GLB là nhị phân tập tin định dạng đại diện của 3D Mô hình được lưu trong GL Định Dạng Truyền (glTF). Thông tin về 3D mô hình chẳng hạn như nút hệ thống phân cấp, máy ảnh, vật liệu, hình ảnh động và mắt lưới trong định dạng nhị phân. Này định dạng nhị phân cửa hàng các glTF Tài Sản (JSON,. Bin và hình ảnh) trong một Binary blob. Nó cũng tránh các vấn đề của Tăng trong tập tin Kích thước mà xảy ra trong trường hợp của glTF. GLB định dạng tập tin kết quả trong nhỏ gọn tập tin kích thước, nhanh chóng tải, hoàn chỉnh 3D cảnh đại diện, và khả năng mở rộng cho phát triển hơn nữa. Các định dạng sử dụng mô hình/gltf-Nhị Phân như MIME loại.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Khác Hỗ Trợ Ứng Dụng để Tạo Ra Đám Mây Điểm để Định Dạng" subTitle="Sử dụng C#, Một cũng có thể tạo ra đám mây điểm để nhiều định dạng tập tin khác bao gồm." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/3mf/" name="3MF" description="3D sản xuất Định Dạng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/amf/" name="AMF" description="Phụ gia Sản Xuất Định Dạng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/ase/" name="ASE" description="2D Hoạt Hình Tập Tin" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/dae/" name="DAE" description="Kỹ thuật số Tài Sản Trao Đổi" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/dxf/" name="DXF" description="Vẽ Trao Đổi Định Dạng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/fbx/" name="FBX" description="3D định dạng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/3ds/" name="3DS" description="3D Studio Lưới Tập Tin Định Dạng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/gltf/" name="GLTF" description="GL Định Dạng Truyền" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/jt/" name="JT" description="Jupiter Tessellation Tập Tin" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/obj/" name="OBJ" description="3D tập tin Định Dạng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/ply/" name="PLY" description="Đa giác Tập Tin Định Dạng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/rvm/" name="RVM" description="AVEVA Thiết Kế Nhà Máy Mô Hình" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/stl/" name="STL" description="Hoán đổi cho nhau 3D Bề Mặt Hình Học" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/vrml/" name="VRML" description="Thực Tế ảo Mô Hình Ngôn Ngữ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/x/" name="X" description="DirectX Hình Ảnh Mô Hình" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/usd/" name="USD" description="Phổ Cảnh Mô Tả" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/usdz/" name="USDZ" description="Phổ Cảnh Mô Tả Zip Lưu Trữ" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}