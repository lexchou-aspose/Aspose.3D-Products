---
title: C# 를 통해 USDZ 에서 PLY 로 변환 
description: .NET API 를 사용하여 USDZ 및 기타 3D 파일을 변환
url: /ko/net/conversion/usdz-to-ply/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: PLY
otherformats: AMF DRC HTML FBX DAE ASE JT RVM 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C# 를 통해 USDZ 에서 PLY 로 변환" h2=".NET 프레임 워크, .NET 코어 및 Mono 를 사용하여 USDZ 및 기타 3D 파일을 내보내기" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="USDZ 장면을 PLY 로 C# 로 내보내기" %}}
1. 의 생성자를 사용하여 USDZ 파일을 로드 [장면](https://apireference.aspose.com/3d/net/aspose.threed/scene) 클래스2. 전화 [장면. 저장](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 방법
3. Pass 출력 파일 이름. 첫 번째 매개 변수로 ply 확장
4. 에서 'PLY' 필드 값을 지정하십시오. [파일 형식](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) 클래스
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D 형식 변환 API for .NET" %}}
명령 줄에서 '''nuget Install Aspose.3d ''또는 ''install-Package Aspose.3D'' '가있는 비주얼 스튜디오의 패키지 관리자 콘솔을 통해 설치하십시오.

또는 ZIP 파일에서 오프라인 MSI 설치 프로그램 또는 dll을 가져옵니다. [다운로드](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="USDZ ~ PLY 변환에 대한 C# 코드" gistPath="" %}}
```cs
// 장면의 객체에 USDZ 로드 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// USDZ 을 PLY 로 저장 
scene.Save("output.ply", Aspose.ThreeD.FileFormat.PLY);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}