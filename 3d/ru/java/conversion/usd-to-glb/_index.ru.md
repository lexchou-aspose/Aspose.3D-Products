﻿---
title: Преобразование USD в GLB через Java
weight: 530
url: /ru/java/conversion/usd-to-glb/ 
description: Пример кода преобразования Java для формата USD в файл GLB. Используйте этот пример кода для преобразования USD в GLB в любом веб-приложении или настольном приложении Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование USD в GLB через Java" h2="Преобразование USD в GLB с использованием библиотеки Java без какого-либо программного обеспечения для моделирования 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="USD" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать USD в GLB с помощью Java" %}}

 Чтобы преобразовать USD в GLB, мы будем использовать
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API – это многофункциональная, мощная и простая в использовании платформа преобразования API for Java. Вы можете скачать его последнюю версию прямо с
 [Мавен](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 и установите его в своем проекте на основе Maven, добавив следующие конфигурации в файл pom.xml.

{{% blocks/products/pf/agp/code-block title="Репозиторий" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://репозиторий.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Зависимость" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-3d</artifactId>
<version>version of aspose-3d API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию USD в GLB через Java" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты Java могут легко преобразовать файл USD в GLB, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл USD через конструктор класса Scene1. Вызовите метод Scene.save с форматом GLB.1. Проверить результирующий файл GLB по указанному пути
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования Java убедитесь, что выполнены следующие предварительные требования.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с Java средой выполнения для приложений JSP/JSF и настольных приложений.- Получите последнюю версию Aspose.3D for Java непосредственно из Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="USD в GLB Java Исходный код преобразования" offSpacer="" %}}

```cs
// Загрузите исходный файл USD
Scene scene = new Scene("sourceFile.usd");
// Преобразование сцены 3D в файл в двоичном формате GLTF
scene.save("output.glb", FileFormat.GLTF2_BINARY)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Преобразование USD в GLB демонстрации в реальном времени" sectionDescription="[Преобразовать USD в GLB](https://products.aspose.app/3d/conversion/usd-to-glb) прямо сейчас, посетив наш веб-сайт Live Demos. Живая демонстрация имеет следующие преимущества" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл USD, и он будет мгновенно преобразован в GLB." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы получите ссылку для скачивания." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Библиотека управления сценами" %}}

 Aspose.3D – это CAD и Gameware API для загрузки, изменения и преобразования файлов 3D. API является автономным и не требует никакого 3D программного обеспечения для моделирования или визуализации. Можно легко использовать API для USD, Discreet3DS, WavefrontOBJ, STL (ASCII, двоичный), Universal3D, FBX (ASCII, двоичный), Collada, glTF, PLY, GLB, DirectX и другие форматы. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="USD" readMoreLink="https://docs.fileformat.com/3d/usd/" >}}

Файл с расширением .usd представляет собой формат универсального описания сцены, который кодирует данные для обмена данными и дополнения между приложениями для создания цифрового контента. Разработанный Pixar, USD позволяет обмениваться элементарными ресурсами (например, моделями) или анимацией.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}

GLB – это представление в формате двоичного файла моделей 3D, сохраненных в формате передачи GL (glTF). Информация о моделях 3D, такая как иерархия узлов, камеры, материалы, анимация и сетки в двоичном формате. В этом двоичном формате ресурс glTF (JSON, .bin и изображения) хранится в двоичном двоичном объекте. Это также позволяет избежать проблемы увеличения размера файла, которая происходит в случае glTF. Формат файла GLB обеспечивает компактный размер файла, быструю загрузку, полное представление сцены 3D и расширяемость для дальнейшего развития. Формат использует model/gltf-binary в качестве типа MIME.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать USD во многие другие форматы файлов, включая некоторые из перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-gltf/" name="USD К GLTF" description="Файл формата передачи GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-glb/" name="USD К GLB" description="Двоичный формат передачи GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-pdf/" name="USD К PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-fbx/" name="USD К FBX" description="Обменный файл Autodesk FBX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-stl/" name="USD К STL" description="Файл стереолитографии" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-obj/" name="USD К OBJ" description="Wavefront 3D Объектный файл" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-3ds/" name="USD К 3DS" description="3D Студийная сцена" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-dae/" name="USD К DAE" description="Файл обмена цифровыми активами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-u3d/" name="USD К U3D" description="Universal 3D файл" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-ply/" name="USD К PLY" description="Формат файла многоугольника" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-drc/" name="USD К DRC" description="Google Draco Формат файла" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-rvm/" name="USD К RVM" description="АВЕВА RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-jt/" name="USD К JT" description="JT Открыть файл CAD" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-amf/" name="USD К AMF" description="Файл аддитивного производства" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-html/" name="USD К HTML" description="Язык гипертекстовой разметки" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/usd-to-usdz/" name="USD К USDZ" description="Универсальное описание сцены в сжатом формате" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}