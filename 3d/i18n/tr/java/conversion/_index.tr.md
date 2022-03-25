---
title: Java 3D Biçimleri Dönüştürme
url: /tr/java/conversion/
description: 3D formatlarını amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x'i Java kitaplığı aracılığıyla Java kodla dönüştürün.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="3D Yoluyla Dönüştürme Biçimleri" h2="Çapraz platform Java uygulamaları oluşturmak için herhangi bir 3D modelleme ve yazılım kurulumu oluşturmadan 3D dosya formatlarını dönüştürün." >}}

{{% blocks/products/pf/feature-page-summary %}}
Üç boyutlu grafik uygulamaları oluşturmak, düzenlemek, işlemek ve kaydetmek için **Java 3D API**, herhangi bir 3D modelleme ve oluşturma yazılımı yüklemeden bu tür özellikleri yapmak için yüksek düzeyde yöntemler sağlar. Çok azı farklı üç boyutlu geometrik şekillerin ağını oluşturur, 3D sahne dosyası oluşturur, Küp üzerinde normaller veya UV oluşturur, öğeleri biçimlendirir, animasyon özelliği ekler ve daha fazlasını ekler. 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="3D Dosyayı farklı biçimlere dönüştürün" %}}
Dönüşüm süreci basittir. Sadece 3D kaynağını kullanarak dosyayı yükleyin [Sahne sınıfı](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene). Sahne düğümler, geometriler, dokular, malzemeler, animasyon, pozlar, alt sahneler vb. [Seçenekleri kaydet](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) AmfSaveOptions, ColladaSaveOptions, Discreet3dsSaveOptions, DracoSaveOptions, FbxSaveOptions, GltfSaveOptions, RvmSaveOptions, RvmSaveOptions, U3dSaveOptions vb. Gibi özellikleri ayarlayın. Son olarak kaydetme yöntemini çıktı dosyası ve oluşturulan hedef biçim kaydetme seçenekleri nesnesi ile kaydedin. Dahası, API programcıları kullanmak 3D sahneyi HTML olarak bile kaydedebilir.


{{% blocks/products/pf/feature-page-code h3="Java AMF ila 3DS Dönüşüm için kod" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="3D Scene\'ı Java aracılığıyla HTML \'e dönüştürün" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}