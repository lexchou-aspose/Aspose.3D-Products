---
title: Java 3D 형식 변환
url: /ko/java/conversion/
description: 3D 라이브러리를 통해 Java 코드의 몇 줄로 amf 3ds amf amf ase att dra drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x를 변환합니다.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D 을 통한 형식 변환 Java" h2="3D 모델링 및 렌더링 소프트웨어 설치없이 3D 파일 형식을 변환하여 크로스 플랫폼 Java 응용 프로그램을 만듭니다." >}}

{{% blocks/products/pf/feature-page-summary %}}
3 차원 그래픽 응용 프로그램 작성, 편집, 조작 및 저장을 위해, ** Java 3D API ** 는 3D 모델링 및 렌더링 소프트웨어를 설치하지 않고도 이러한 기능을 수행하는 높은 수준의 방법을 제공합니다. 다른 3 차원 기하학적 모양의 메쉬를 만들고, 3D 장면 파일을 만들고, 큐브에 노멀 또는 UV 설정, 요소 형식, 애니메이션 속성 추가 등은 거의 없습니다. 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="3D 파일을 다른 형식으로 변환" %}}
변환 과정은 간단합니다. 를 사용하여 소스 3D 파일을 로드하십시오. [장면 클래스](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene). 장면은 노드, 기하학, 텍스처, 재료, 애니메이션, 포즈, 하위 장면 등을 갖는 최상위 객체이므로 관련 [옵션 저장](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) AmfSaveOptions, ColladaSaveOptions, Discreet3dsSaveOptions, FbxSaveOptions, GltfSaveOptions, rvmsavoptions, stlsavefoptions, U3dSaveOptions 등과 같은 속성을 적절하게 설정합니다. 마지막으로 출력 파일과 함께 저장 방법을 호출하고 생성 된 대상 형식 저장 옵션 개체. 또한 API 프로그래머를 사용하면 3D 장면을 HTML 로 저장할 수도 있습니다.


{{% blocks/products/pf/feature-page-code h3="AMF ~ 3DS 변환에 대한 Java 코드" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Java 를 통해 3D 장면을 HTML 로 변환" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}