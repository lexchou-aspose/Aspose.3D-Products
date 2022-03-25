﻿---
title: Convertir ASE a FBX a través de C# 
weight: 2000
url: /es/net/conversion/ase-to-fbx/ 
description: Código de muestra para la conversión de ASE a FBX C#. Use API código de ejemplo para los archivos por lotes ASE a la conversión de FBX dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir ASE a FBX a través de C#" h2="Render ASE como FBX sin ningún 3D software de modelado y renderizado." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir ASE a FBX usando C#" %}}

 Para convertir ASE a FBX, usaremos
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API que es una plataforma de conversión y manipulación de documentos rica en funciones, potente y fácil de usar API para C#. Abierto
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Gestor de paquetes, búsqueda
 Aspose.3D 
 E instalar. También puede utilizar el siguiente comando de la Consola del Administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Comando de consola de Package Manager" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir ASE a FBX a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programadores pueden cargar y convertir fácilmente ASE archivos a FBX en solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargar ASE archivo a través del constructor de la clase Scene1. Crear una instancia de FbxSaveOptions1. Establecer FBX propiedades específicas para la conversión avanzada1. Llame al método Scene.Save1. Pase la ruta de salida con FBX extensión de archivo y objeto de FbxSaveOptions1. Comprobar FBX archivo resultante en la ruta especificada
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de conversión .NET, asegúrese de que tiene los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core, Mono.- Entorno de desarrollo como Microsoft Visual Studio.- Aspose.3D for .NET DLL al que se hace referencia en su proyecto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de ejemplo muestra la conversión de ASE a FBX C#" offSpacer="" %}}

```cs
// Cargar el ASE en un objeto de Escena 
var document = new Aspose.ThreeD.Scene("template.ase");
// Crear una instancia de FbxSaveOptions 
var options = new Aspose.ThreeD.Formats.FbxSaveOptions();
// Guardar ASE como FBX 
document.Save("output.fbx", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicación gratuita para convertir ASE a FBX" sectionDescription="Consulte nuestras demostraciones en vivo para [Conversión de ASE a FBX](https://products.aspose.app/3d/conversion/ase-to-fbx) Con los siguientes beneficios." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su ASE archivo y presione el botón \"Convertir\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá instantáneamente el enlace de descarga para el archivo FBX resultante." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Una biblioteca de procesamiento de archivos 3D para manipular 3D archivos sin ningún software de modelado y renderizado. El 3D API es compatible con Discreet3DS, WavefrontOBJ, FBX (ASCII, binario), STL (ASCII, binario), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formatos de archivo y más. Los desarrolladores pueden crear, leer, convertir, modificar y controlar la sustancia de 3D formatos de documentos fácilmente.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}
Un archivo ASE es una animación o gráficos 2D que contienen capas, marcos, paletas, etiquetas y parámetros.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="fbx" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox, es un popular formato de archivo 3D que fue desarrollado originalmente por Kaydara para MotionBuilder. Fue adquirido por Autodesk Inc en 2006 y ahora es uno de los principales 3D formatos de intercambio utilizados por muchas 3D herramientas. FBX está disponible en formato de archivo binario y ASCII. El formato se estableció para proporcionar interoperabilidad entre aplicaciones de creación de contenido digital. Hay muchas herramientas disponibles para la conversión de/a FBX formato de archivo.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones soportadas" subTitle="También puede convertir ASE en muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-3ds/" name="ASE A 3DS" description="3D Malla DOS de estudio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-amf/" name="ASE A AMF" description="Formato de fabricación aditiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-dae/" name="ASE A DAE" description="Intercambio de activos digitales" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-html/" name="ASE A HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-obj/" name="ASE A OBJ" description="3D Formato de archivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-pdf/" name="ASE A PDF" description="Formato de documento portátil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-ply/" name="ASE A PLY" description="Formato de archivo Polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-rvm/" name="ASE A RVM" description="Modelo de diseño de planta AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-stl/" name="ASE A STL" description="Geometría de superficie intercambiable 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ase-to-u3d/" name="ASE A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}