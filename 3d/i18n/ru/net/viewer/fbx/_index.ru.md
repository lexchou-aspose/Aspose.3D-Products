﻿---
title: Просмотр форматов файлов FBX через .NET 
weight: 910
url: /ru/net/viewer/fbx/ 
description: Исходный код C# для загрузки, визуализации и отображения документов FBX на .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="FBX Просмотр файлов for .NET" h2="Разначение файлов FBX без программного обеспечения для моделирования и рендеринга 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как просмотреть файл FBX с использованием C#" %}}

 Для просмотра FBX файла мы будем использовать
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, который является многофункциональным, мощным и простым в использовании API для платформы C#, которая будет использоваться с любым средством просмотра. Открытая
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Менеджер пакетов, поиск
 **Aspose.3D** 
 И установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги для просмотра FBX через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D упрощает для разработчиков просмотр файла FBX с несколькими строками кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузить файл FBX через конструктор класса Scene1. Создать экземпляр Html5SaveOptions1. Установить свойства для расширенного форматирования1. Вызовите метод Scene.Save с объектом Html5SaveOptions1. Проверьте результирующий файл HTML в браузере по умолчанию
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к системе" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono- Среда разработки, такая как Microsoft Visual Studio- Aspose.3D for .NET, упомянутые в вашем проекте
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Код C# для просмотра FBX" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// Загрузить сцену FBX через экземпляр сцены
var scene = new ThreeD.Scene("template.fbx");
// Создать объект Html5SaveOptions и задать свойства для форматирования
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // Выключить сетку
    ShowGrid = false,
    // Выключить пользовательский интерфейс
    ShowUI = false
};

// Сохраните сцену 3D как HTML5
scene.Save(output, options);
// Загрузка результирующего HTML в браузере по умолчанию
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="О Aspose.3D for .NET API" %}}

 Aspose.3D-это CAD и Gameware API для загрузки, изменения и преобразования файлов 3D. API является автономным и не требует каких-либо программ моделирования или рендеринга 3D. Можно легко использовать API для форматов Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX и других. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для просмотра FBX" sectionDescription="Проверьте наши живые демонстрации, чтобы [Просмотр FBX](https://products.aspose.app/3d/viewer/fbx) Со следующими преимуществами." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать или настраивать что-либо" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать или компилировать код" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите FBX файл и нажмите кнопку \"Просмотреть\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Загрузите FBX файл по ссылке, если требуется" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox-это популярный формат файлов 3D, изначально разработанный Kaydara для MotionBuilder. Он был приобретен Autodesk Inc в 2006 году и в настоящее время является одним из основных форматов обмена 3D, используемых многими инструментами 3D. FBX доступен как в двоичном, так и в формате файлов ASCII. Формат был создан для обеспечения совместимости между приложениями для создания цифрового контента. Существует множество инструментов для преобразования из/в формат файла FBX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые форматы Viewer" subTitle="Используя C#, можно также просматривать многие другие форматы файлов, включая." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Студийная сетка DOS" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="Формат производства 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="Аддитивный формат производства" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="Файл 2D анимации" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="Обмен цифровых активов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="Формат обмена чертежами" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="Двоичное представление файлов 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="Формат передачи GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="Файл Jupiter Tessellation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="Формат файла 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="Формат файла многоугольника" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="Модель дизайна завода AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="Сменная геометрия поверхности 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="Язык моделирования виртуальной реальности" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="X" description="Изображение модели DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="Формат архивирования ZIP" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}