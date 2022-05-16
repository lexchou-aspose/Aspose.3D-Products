﻿---
title: Преобразование DRC в PDF через C# 
url: /ru/net/conversion/drc-to-pdf/ 
description: Пример кода для преобразования DRC в PDF C#. Используйте пример кода API для пакетного преобразования DRC файлов в PDF в VB.NET, Asp.NET или любом приложении на основе .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование DRC в PDF через C#" h2="Визуализировать DRC как PDF без какого-либо программного обеспечения для моделирования и визуализации 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как преобразовать DRC в PDF с помощью C#" %}}

 Чтобы преобразовать DRC в PDF, мы будем использовать
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

{{% blocks/products/pf/agp/feature-section-col title="Действия по преобразованию DRC в PDF через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Программисты .NET могут легко загружать и преобразовывать файлы DRC в PDF, написав всего несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузите файл DRC через конструктор класса Scene1. Создайте экземпляр AmfSaveOptions1. Установите определенные свойства PDF для расширенного преобразования1. Вызов метода Scene.Save1. Передайте выходной путь с расширением файла PDF и объектом PdfSaveOptions1. Проверить результирующий файл PDF по указанному пути
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Системные Требования" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования .NET убедитесь, что выполнены следующие предварительные требования.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono.- Среда разработки, такая как Microsoft Visual Studio.- Aspose.3D for .NET DLL, на которые ссылается ваш проект.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В этом примере кода показано преобразование DRC в PDF C#" offSpacer="" %}}

```cs
// загрузить DRC в объект сцены 
var document = new Aspose.ThreeD.Scene("template.drc");
// создать экземпляр PdfSaveOptions 
var options = new Aspose.ThreeD.Formats.PdfSaveOptions();
// сохранить DRC как PDF 
document.Save("output.pdf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для преобразования DRC в PDF" sectionDescription="Проверьте наши живые демонстрации для [Преобразование DRC в PDF](https://products.aspose.app/3d/conversion/drc-to-pdf) со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл DRC и нажмите кнопку \"Конвертировать\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы сразу же получите ссылку для скачивания результирующего файла PDF." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Библиотека обработки файлов 3D для управления файлами 3D без какого-либо программного обеспечения для моделирования и визуализации. 3D API поддерживает Discreet3DS, WavefrontOBJ, FBX (ASCII, двоичный), STL (ASCII, двоичный), Universal3D, Collada, glTF, GLB, PLY, DirectX, форматы файлов Google Draco и многое другое. Разработчики могут легко создавать, читать, преобразовывать, изменять и контролировать содержание форматов документов 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}
Файл с расширением .drc представляет собой сжатый файл в формате 3D, созданный с помощью библиотеки Google Draco. Google предлагает Draco как библиотеку с открытым исходным кодом для сжатия и распаковки 3D геометрических сеток и облаков точек, а также улучшает хранение и передачу 3D графики. Он кодирует входные данные и сохраняет их как файл .drc. На принимающей стороне API считывает файлы .drc и может выводить их в виде файлов PLY или OBJ. Сжатый выходной файл позволяет пользователям быстрее загружать приложения и обеспечивает быструю загрузку графики 3D в браузерах.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="pdf" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable Document Format (PDF) — это тип документа, созданный Adobe еще в 1990-х годах. Цель этого формата файла состояла в том, чтобы ввести стандарт для представления документов и других справочных материалов в формате, который не зависит от прикладного программного обеспечения, аппаратного обеспечения, а также операционной системы. Файлы PDF можно открывать в Adobe Acrobat Reader/Writer, а также в большинстве современных браузеров, таких как Chrome, Safari, Firefox, с помощью расширений/плагинов. Большинство коммерчески доступных комплектов программного обеспечения также предлагают преобразование своих документов в файловый формат PDF без необходимости использования каких-либо дополнительных программных компонентов. Таким образом, формат файла PDF имеет полную возможность содержать такую информацию, как текст, изображения, гиперссылки, поля форм, мультимедийные файлы, цифровые подписи, вложения, метаданные, геопространственные функции и объекты 3D, которые могут стать частью источника. документ.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}