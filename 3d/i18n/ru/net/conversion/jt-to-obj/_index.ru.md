﻿---
title: Конвертировать JT в OBJ через C# 
weight: 1610
url: /ru/net/conversion/jt-to-obj/ 
description: Пример кода для преобразования JT в OBJ C#. Используйте API пример кода для пакетного преобразования JT файлов в OBJ в VB.NET, Asp.NET или любом приложении на основе .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Конвертировать JT в OBJ через C#" h2="Отправка JT как OBJ без программного обеспечения для моделирования и рендеринга 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как конвертировать JT в OBJ с помощью C#" %}}

 Чтобы конвертировать JT в OBJ, мы будем использовать
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, который представляет собой многофункциональный, мощный и простой в использовании документ обработки и преобразования API для платформы C#. Открытая
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Менеджер пакетов, поиск
 Aspose.3D 
 И установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги для преобразования JT в OBJ через C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET программисты могут легко загружать и конвертировать JT файлы в OBJ всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузить файл JT через конструктор класса Scene1. Создать экземпляр ObjSaveOptions1. Установите специальные свойства OBJ для расширенного преобразования1. Вызовите метод Scene.Save1. Передайте выходной путь с расширением файла OBJ и объектом ObjSaveOptions1. Проверьте результирующий файл OBJ по указанному пути
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к системе" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования .NET убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono.- Среда разработки, такая как Microsoft Visual Studio.- Aspose.3D for .NET DLL, упомянутые в вашем проекте.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Этот пример кода показывает JT в OBJ C# преобразования" offSpacer="" %}}

```cs
// Загрузить JT в объект сцены 
var document = new Aspose.ThreeD.Scene("template.jt");
// Создать экземпляр ObjSaveOptions 
var options = new Aspose.ThreeD.Formats.ObjSaveOptions();
// Сохранить JT как OBJ 
document.Save("output.obj", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для преобразования JT в OBJ" sectionDescription="Проверьте наши живые демо для [Преобразование JT в OBJ](https://products.aspose.app/3d/conversion/jt-to-obj) Со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать или настраивать что-либо." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Не нужно писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите свой JT файл и нажмите кнопку \"Конвертировать\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы мгновенно получите ссылку для загрузки полученного файла OBJ." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Библиотека обработки файлов 3D для управления файлами 3D без какого-либо программного обеспечения для моделирования и рендеринга. 3D API поддерживает Discreet3DS, WavefrontOBJ, FBX (ASCII, двоичный), STL (ASCII, двоичный), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco форматы файлов и многое другое. Разработчики могут легко создавать, читать, преобразовывать, изменять и контролировать содержание форматов документов 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JT" readMoreLink="https://docs.fileformat.com/3d/jt/" >}}
JT (Jupiter Tessellation)-это эффективный, ориентированный на отрасль и гибкий стандартизированный по ISO формат данных 3D, разработанный Siemens PLM Software. Механические CAD области аэрокосмической, автомобильной промышленности и тяжелого оборудования используют JT в качестве наиболее ведущего формата визуализации 3D. Формат JT-это граф сцены, который поддерживает атрибуты и узлы, специфичные для CAD. Сложные методы сжатия используются для хранения данных фасета (треугольников). Этот формат структурирован для поддержки визуальных атрибутов, информации о продукте и производстве (PMI), а также метаданных. Существует хорошая поддержка асинхронной потоковой передачи контента. В тяжелой механической промышленности профессионалы используют файл JT в своих решениях CAD и программных программах управления жизненным циклом продукта (PLM) для изучения геометрии сложных товаров.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="obj" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
OBJ файлы используются приложением Advanced Visualizer Wavefront для определения и хранения геометрических объектов. Обратная и прямая передача геометрических данных возможна через OBJ файлов. Обе многоугольные геометрии, такие как точки, линии, вершины текстуры, грани и геометрия свободной формы (кривые и поверхности), поддерживаются форматом OBJ. Этот формат не поддерживает анимацию или информацию, связанную со светом и положением сцен. Файл OBJ обычно является конечным продуктом процесса моделирования 3D, созданного с помощью CAD (компьютерное проектирование). Порядок хранения вершин по умолчанию равен против часовой стрелки, избегая явного объявления нормалей лица. Хотя OBJ файлы объявляют информацию о масштабе в строке комментариев, но никакие единицы не были объявлены для OBJ координат.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать JT во многие другие форматы файлов, включая несколько перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-3ds/" name="JT ДО 3DS" description="3D Студийная сетка DOS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-amf/" name="JT ДО AMF" description="Аддитивный формат производства" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-dae/" name="JT ДО DAE" description="Обмен цифровых активов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-fbx/" name="JT ДО FBX" description="Формат 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-html/" name="JT ДО HTML" description="Язык разметки текста Hyper" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-pdf/" name="JT ДО PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-ply/" name="JT ДО PLY" description="Формат файла многоугольника" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-rvm/" name="JT ДО RVM" description="Модель дизайна завода AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-stl/" name="JT ДО STL" description="Сменная геометрия поверхности 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-u3d/" name="JT ДО U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}