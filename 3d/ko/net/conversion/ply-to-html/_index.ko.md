﻿---
title: C#를 통해 PLY을 HTML로 변환 
weight: 3080
url: /ko/net/conversion/ply-to-html/ 
description: PLY에서 HTML로의 C# 변환을 위한 샘플 코드. VB.NET, Asp.NET 또는 모든 .NET 기반 애플리케이션 내에서 배치 PLY 파일을 HTML로 변환하는 API 예제 코드를 사용합니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#를 통해 PLY을 HTML로 변환" h2="3D 모델링 및 렌더링 소프트웨어 없이 PLY을 HTML로 렌더링합니다." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PLY" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#를 사용하여 PLY을 HTML로 변환하는 방법" %}}

 PLY을(를) HTML(으)로 변환하기 위해 다음을 사용합니다.
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API은(는) C# 플랫폼용으로 기능이 풍부하고 강력하며 사용하기 쉬운 문서 조작 및 변환API입니다. 열려있는
 [누겟](https://www.nuget.org/packages/aspose.3d) 
 패키지 관리자, 검색
 Aspose.3D 
 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="패키지 관리자 콘솔 명령" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#를 통해 PLY을 HTML로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 프로그래머는 몇 줄의 코드로 PLY 파일을 쉽게 로드하고 HTML로 변환할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. Scene 클래스의 생성자를 통해 PLY 파일 로드1. HtmlSaveOptions의 인스턴스 만들기1. 고급 변환을 위한 HTML 특정 속성 설정1. Scene.Save 메서드 호출1. HTML 파일 확장명 및 HtmlSaveOptions 개체로 출력 경로 전달1. 지정된 경로에서 결과 HTML 파일 확인
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 .NET 변환 코드를 실행하기 전에 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Mono 호환 OS.- Microsoft Visual Studio와 같은 개발 환경.- Aspose.3D for .NET 프로젝트에서 참조되는 DLL입니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="이 샘플 코드는 PLY에서 HTML로의 C# 전환을 보여줍니다." offSpacer="" %}}

```cs
// Scene의 객체에 PLY 로드 
var document = new Aspose.ThreeD.Scene("template.ply");
// HtmlSaveOptions의 인스턴스 만들기 
var options = new Aspose.ThreeD.Formats.Html5SaveOptions();
// PLY을 HTML로 저장 
document.Save("output.html", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="PLY을(를) HTML(으)로 변환하는 무료 앱" sectionDescription="라이브 데모를 확인하십시오. [PLY에서 HTML로의 전환](https://products.aspose.app/3d/conversion/ply-to-html) 다음과 같은 혜택이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 아무것도 다운로드하거나 설정할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" PLY 파일을 업로드하고 \"변환\" 버튼을 누르기만 하면 됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 결과 HTML 파일에 대한 다운로드 링크를 즉시 얻을 수 있습니다." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 모델링 및 렌더링 소프트웨어 없이 3D 파일을 조작하는 3D 파일 처리 라이브러리. 3D API는 Discreet3DS, WavefrontOBJ, FBX(ASCII, 바이너리), STL(ASCII, 바이너리), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco 파일 형식 등 개발자는 3D 문서 형식의 내용을 쉽게 생성, 읽기, 변환, 수정 및 제어할 수 있습니다.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}
PLY, 다각형 파일 형식은 다각형 모음으로 설명되는 그래픽 개체를 저장하는 3D 파일 형식을 나타냅니다. 이 파일 형식의 목적은 광범위한 모델에 유용할 만큼 충분히 일반적이고 간단하고 쉬운 파일 형식을 설정하는 것입니다. PLY 파일 형식은 ASCII 및 바이너리 형식으로 제공되어 압축 저장 및 빠른 저장 및 로드를 지원합니다. 파일 형식은 3D 파일 읽기를 지원하는 다양한 애플리케이션에서 사용됩니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="html" readMoreLink="https://docs.fileformat.com/web/html/" >}}
HTML(Hyper Text Markup Language)는 브라우저에 표시하기 위해 생성된 웹페이지용 확장 프로그램입니다. 웹 언어로 알려진 HTML은(는) 웹 페이지의 일부로 표시되어야 하는 새로운 정보 요구 사항의 요구 사항과 함께 발전했습니다. 최신 변형은 HTML 5로 알려져 있으며 언어 작업에 많은 유연성을 제공합니다. HTML 페이지는 호스트되는 서버에서 수신되거나 로컬 시스템에서도 로드될 수 있습니다. 각 HTML 페이지는 양식, 텍스트, 이미지, 애니메이션, 링크 등과 같은 HTML 요소로 구성됩니다. 이러한 요소는 img, a, p 및 각 태그에 시작과 끝이 있는 여러 태그로 표시됩니다. . 또한 전체 레이아웃 표현을 위해 JavaScript 및 CSS(스타일 시트)와 같은 스크립팅 언어로 작성된 응용 프로그램을 포함할 수 있습니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="기타 지원되는 변환" subTitle="PLY을(는) 아래 나열된 몇 가지를 포함하여 다른 많은 파일 형식으로 변환할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-3ds/" name="PLY ~ 3DS" description="3D 스튜디오 DOS 메시" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-amf/" name="PLY ~ AMF" description="적층 제조 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-dae/" name="PLY ~ DAE" description="디지털 자산 교환" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-fbx/" name="PLY ~ FBX" description="3D 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-obj/" name="PLY ~ OBJ" description="3D 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-pdf/" name="PLY ~ PDF" description="휴대용 문서 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-rvm/" name="PLY ~ RVM" description="AVEVA 플랜트 설계 모델" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-stl/" name="PLY ~ STL" description="교체 가능한 3D 표면 기하학" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-u3d/" name="PLY ~ U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}