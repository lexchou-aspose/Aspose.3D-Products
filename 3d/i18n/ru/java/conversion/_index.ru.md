---
title: Java 3D Преобразование форматов
url: /ru/java/conversion/
description: Конвертируйте форматы 3D amf 3ds amf ase att dae drc dxf fbx gltf jt obj ply rvm stl u3d usdz usd vrml x с несколькими строками кода Java через библиотеку Java.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование форматов 3D через Java" h2="Конвертируйте форматы файлов 3D без установки программного обеспечения для моделирования и рендеринга 3D для создания кроссплатформенных приложений Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
Для создания, редактирования, управления и сохранения трехмерных графических приложений **Java 3D API** предоставляет высокий уровень методов для создания таких функций без установки любого 3D программного обеспечения для моделирования и рендеринга. Немногие создают сетку различных трехмерных геометрических форм, создают файл сцены 3D, настраивают нормали или УФ-излучение на Кубе, форматируют элементы, добавляют свойство анимации и многое другое. 

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Конвертировать 3D файл в разные форматы" %}}
Процесс преобразования прост. Просто загрузите исходный файл 3D с помощью [Класс сцены](https://apireference.aspose.com/3d/java/com.aspose.threed/Scene). Поскольку сцена-это объект верхнего уровня, имеющий узлы, геометрию, текстуры, материалы, анимацию, позы, подсцены и т. Д. Создайте соответствующий [Сохранить опции](https://apireference.aspose.com/3d/java/com.aspose.threed/SaveOptions) Такие как AmfSaveOptions, ColladaSaveOptions, Discreet3dsSaveOptions, DracoSaveOptions, FbxSaveOptions, GltfSaveOptions, RvmSaveOptions, StlSaveOptions, U3dSaveOptions и т. д. и задают свойства соответственно. Наконец вызовите метод сохранения с помощью выходного файла и созданного целевого формата save options object. Более того, с помощью API программисты могут даже сохранить 3D сцену как HTML.


{{% blocks/products/pf/feature-page-code h3="Код Java для преобразования AMF в 3DS" %}}

{{< gist "aspose-com-gists" "766e923b86deeccd14d69376efe862d8" "convert-amf-to-3ds.java" >}}

{{% /blocks/products/pf/feature-page-code %}}


{{% blocks/products/pf/feature-page-code h3="Конвертировать 3D Сцена в HTML через Java" %}}

{{< gist "aspose-com-gists" "0672215ca08d7566bd64d657e2b228a7" "src-java-examples-loadsave-SaveOptions-html5SaveOption.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="stl-to-obj obj-to-stl obj-to-3ds dae-to-obj fbx-to-stl" >}}