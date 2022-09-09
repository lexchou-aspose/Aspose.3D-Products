---
title: C#를 통해 USDZ을 X로 변환 
description: .NET API을(를) 사용하여 USDZ 및 기타 3D 파일 변환
url: /ko/net/conversion/usdz-to-x/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: X
otherformats: HTML FBX STL DRC RVM DAE 3MF ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C#를 통해 USDZ을 X로 변환" h2=".NET Framework, .NET Core 및 Mono를 사용하여 USDZ 및 기타 3D 파일 내보내기" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#를 사용하여 USDZ 장면을 X로 내보내기" %}}
1. 생성자를 사용하여 USDZ 파일 로드 [장면](https://apireference.aspose.com/3d/net/aspose.threed/scene) 수업2. 전화 [장면.저장](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 방법
3. 첫 번째 매개변수로 확장자가 .x인 출력 파일 이름을 전달합니다.
4. 'XBinary' 필드 값 지정 [파일 형식](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) 수업
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D 형식 변환 API for .NET" %}}
명령줄에서 ```nuget install Aspose.3d```로 설치하거나 ```Install-Package Aspose.3D```를 사용하여 Visual Studio의 패키지 관리자 콘솔을 통해 설치합니다.

또는 ZIP 파일에서 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다. [다운로드](https://releases.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# USDZ에서 X로의 변환을 위한 코드" gistPath="" %}}
```cs
// Scene의 객체에 USDZ 로드 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// USDZ을 X로 저장 
scene.Save("output.x", Aspose.ThreeD.FileFormat.XBinary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}