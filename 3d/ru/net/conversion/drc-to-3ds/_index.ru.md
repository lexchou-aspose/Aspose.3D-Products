﻿---
title: Преобразование DRC в 3DS через C# 
url: /ru/net/conversion/drc-to-3ds/ 
description: Пример кода для преобразования DRC в 3DS C#. Используйте пример кода API для пакетного преобразования DRC файлов в 3DS в VB.NET, Asp.NET или любом приложении на основе .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование DRC в 3DS через C#" h2="Визуализировать DRC как 3DS без какого-либо программного обеспечения для моделирования и визуализации 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="3DS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать DRC в 3DS с помощью C#" %}}

 Чтобы преобразовать DRC в 3DS, мы будем использовать
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API — многофункциональное, мощное и простое в использовании средство обработки и преобразования документов API для платформы C#. Открыть
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 менеджер пакетов, поиск
 Aspose.3D 
 и установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию DRC в 3DS через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты .NET могут легко загружать и преобразовывать файлы DRC в 3DS, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл DRC через конструктор класса Scene1. Создайте экземпляр AmfSaveOptions1. Установите определенные свойства 3DS для расширенного преобразования1. Вызов метода Scene.Save1. Передайте выходной путь с расширением файла 3DS и объектом Discreet3dsSaveOptions.1. Проверить результирующий файл 3DS по указанному пути
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования .NET убедитесь, что выполнены следующие предварительные требования.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono.- Среда разработки, такая как Microsoft Visual Studio.- Aspose.3D for .NET DLL, на которые ссылается ваш проект.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В этом примере кода показано преобразование DRC в 3DS C#" offSpacer="" %}}

```cs
// загрузить DRC в объект сцены 
var document = new Aspose.ThreeD.Scene("template.drc");
// создать экземпляр Discreet3dsSaveOptions 
var options = new Aspose.ThreeD.Formats.Discreet3dsSaveOptions();
// сохранить DRC как 3DS 
document.Save("output.3ds", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для преобразования DRC в 3DS" sectionDescription="Проверьте наши живые демонстрации для [Преобразование DRC в 3DS](https://products.aspose.app/3d/conversion/drc-to-3ds) со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл DRC и нажмите кнопку \"Конвертировать\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы сразу же получите ссылку для скачивания результирующего файла 3DS." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Библиотека обработки файлов 3D для управления файлами 3D без какого-либо программного обеспечения для моделирования и визуализации. 3D API поддерживает Discreet3DS, WavefrontOBJ, FBX (ASCII, двоичный), STL (ASCII, двоичный), Universal3D, Collada, glTF, GLB, PLY, DirectX, форматы файлов Google Draco и многое другое. Разработчики могут легко создавать, читать, преобразовывать, изменять и контролировать содержание форматов документов 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
Файл с расширением .drc представляет собой сжатый файл в формате 3D, созданный с помощью библиотеки Google Draco. Google предлагает Draco как библиотеку с открытым исходным кодом для сжатия и распаковки 3D геометрических сеток и облаков точек, а также улучшает хранение и передачу 3D графики. Он кодирует входные данные и сохраняет их как файл .drc. На принимающей стороне API считывает файлы .drc и может выводить их в виде файлов PLY или OBJ. Сжатый выходной файл позволяет пользователям быстрее загружать приложения и обеспечивает быструю загрузку графики 3D в браузерах.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3ds" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
Файл с расширением 3DS представляет формат файла сетки 3D Studio (DOS), используемый Autodesk 3D Studio. Autodesk 3D Studio существует на рынке файловых форматов 3D с 1990-х годов и теперь превратилась в 3D Studio MAX для работы с 3D моделированием, анимацией и визуализацией. Файл 3DS содержит данные для 3D представления сцен и изображений и является одним из популярных форматов файлов для импорта и экспорта данных 3D. Он учитывает такую информацию, как расположение камер, данные сетки, информацию об освещении, конфигурации области просмотра, данные группы сглаживания, ссылки на растровые изображения и атрибуты для создания вершин и полигонов для рендеринга сцены.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}