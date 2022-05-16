﻿---
title: Chuyển đổi 3DS sang U3D qua C# 
weight: 2140
url: /vi/net/conversion/3ds-to-u3d/ 
description: Mã mẫu cho chuyển đổi 3DS thành U3D C#. Sử dụng API mã mẫu cho hàng loạt tệp 3DS để chuyển đổi U3D trong VB .NET, Asp .NET hoặc bất kỳ ứng dụng dựa trên .NET nào.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Chuyển đổi 3DS sang U3D qua C#" h2="Hiển thị 3DS dưới dạng U3D mà không có bất kỳ 3D phần mềm kết xuất và mô hình hóa nào." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cách chuyển đổi 3DS thành U3D bằng cách sử dụng C#" %}}

 Để chuyển đổi 3DS thành U3D, chúng tôi sẽ sử dụng
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API là một nền tảng thao tác và chuyển đổi tài liệu API giàu tính năng, mạnh mẽ và dễ sử dụng API cho C#. Mở
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 quản lý gói, tìm kiếm
 Aspose.3D 
 và cài đặt. Bạn cũng có thể sử dụng lệnh sau từ Bảng điều khiển Trình quản lý Gói.

{{% blocks/products/pf/agp/code-block title="Lệnh Bảng điều khiển Trình quản lý Gói" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Các bước chuyển đổi 3DS thành U3D qua C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET người lập trình có thể dễ dàng tải và chuyển đổi 3DS tệp thành U3D chỉ trong một vài dòng mã.

{{% /blocks/products/pf/agp/text %}}

1. Tải tệp 3DS qua hàm tạo của lớp Scene1. Tạo một phiên bản của U3dSaveOptions1. Đặt U3D thuộc tính cụ thể cho chuyển đổi nâng cao1. Gọi phương thức Scene.Save1. Chuyển đường dẫn đầu ra với U3D phần mở rộng tệp & đối tượng của U3dSaveOptions1. Kiểm tra tệp U3D kết quả tại đường dẫn được chỉ định
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="yêu cầu hệ thống" %}}

{{% blocks/products/pf/agp/text %}}

 Trước khi chạy mã chuyển đổi .NET, hãy đảm bảo rằng bạn có các điều kiện tiên quyết sau.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows hoặc một hệ điều hành tương thích với .NET Framework, .NET Core, Mono.- Môi trường phát triển như Microsoft Visual Studio.- Aspose.3D for .NET DLL được tham chiếu trong dự án của bạn.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Mã mẫu này hiển thị Chuyển đổi 3DS sang U3D C#" offSpacer="" %}}

```cs
// tải 3DS trong một đối tượng của Scene 
var document = new Aspose.ThreeD.Scene("template.3ds");
// tạo một phiên bản của U3dSaveOptions 
var options = new Aspose.ThreeD.Formats.U3dSaveOptions();
// lưu 3DS dưới dạng U3D 
document.Save("output.u3d", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ứng dụng miễn phí để chuyển đổi 3DS sang U3D" sectionDescription="Kiểm tra các bản trình diễn trực tiếp của chúng tôi cho [Chuyển đổi 3DS thành U3D](https://products.aspose.app/3d/conversion/3ds-to-u3d) với những lợi ích sau đây." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Không cần tải xuống hoặc thiết lập bất cứ thứ gì." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Không cần phải viết bất kỳ mã nào." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Chỉ cần tải lên tệp 3DS của bạn và nhấn nút \"Chuyển đổi\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Bạn sẽ ngay lập tức nhận được liên kết tải xuống cho tệp U3D kết quả." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D Thư viện xử lý tệp để thao tác 3D tệp mà không cần bất kỳ phần mềm kết xuất và mô hình hóa nào. 3D API hỗ trợ Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, Định dạng tệp PLY, DirectX, Google Draco và hơn thế nữa. Các nhà phát triển có thể tạo, đọc, chuyển đổi, sửa đổi và kiểm soát nội dung của 3D các định dạng tài liệu một cách dễ dàng.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
Tệp có phần mở rộng 3DS đại diện cho định dạng tệp lưới 3D Studio (DOS) được Autodesk 3D Studio sử dụng. Autodesk 3D Studio đã có mặt trên thị trường định dạng tệp 3D từ những năm 1990 và hiện đã phát triển thành 3D Studio MAX để làm việc với 3D tạo mô hình, hoạt ảnh và kết xuất. Tệp 3DS chứa dữ liệu để biểu diễn 3D cảnh và hình ảnh và là một trong những định dạng tệp phổ biến để nhập và xuất dữ liệu 3D. Nó xem xét các thông tin như vị trí camera, dữ liệu Mesh, thông tin ánh sáng, cấu hình khung nhìn, dữ liệu nhóm làm mịn, tham chiếu bitmap và các thuộc tính để tạo đỉnh và đa giác để hiển thị cảnh.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="u3d" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}
U3D (Universal 3D) là định dạng tệp nén và cấu trúc dữ liệu cho 3D đồ họa máy tính. Nó chứa thông tin mô hình 3D chẳng hạn như lưới tam giác, ánh sáng, bóng đổ, dữ liệu chuyển động, đường và điểm có màu sắc và cấu trúc. Định dạng này đã được chấp nhận là tiêu chuẩn ECMA-363 vào tháng 8 năm 2005. 3D PDF tài liệu hỗ trợ U3D nhúng đối tượng và có thể xem được trong Adobe Reader (phiên bản 7 trở đi). Định dạng U3D được phát triển nhằm mục đích thiết lập một tiêu chuẩn chung cho việc lưu trữ và trao đổi dữ liệu ba chiều. Tuy nhiên, định dạng được sử dụng chính trong mã hóa cho 3D PDF hơn là được sử dụng làm định dạng trao đổi. Acrobat 3D chuyển đổi loại tệp 3D được hỗ trợ thành U3D hoặc PRC khi chuyển đổi thành PDF.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Các chuyển đổi được hỗ trợ khác" subTitle="Bạn cũng có thể chuyển đổi 3DS thành nhiều định dạng tệp khác, bao gồm một số định dạng được liệt kê bên dưới." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-amf/" name="3DS ĐẾN AMF" description="Định dạng sản xuất phụ gia" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-dae/" name="3DS ĐẾN DAE" description="Trao đổi tài sản kỹ thuật số" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-fbx/" name="3DS ĐẾN FBX" description="3D Định dạng" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-html/" name="3DS ĐẾN HTML" description="Ngôn ngữ đánh dấu siêu văn bản" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-obj/" name="3DS ĐẾN OBJ" description="3D Định dạng Tệp" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-pdf/" name="3DS ĐẾN PDF" description="Định dạng tài liệu di động" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-ply/" name="3DS ĐẾN PLY" description="Định dạng tệp đa giác" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-rvm/" name="3DS ĐẾN RVM" description="Mô hình thiết kế nhà máy AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-stl/" name="3DS ĐẾN STL" description="Hình học bề mặt 3D có thể hoán đổi cho nhau" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}