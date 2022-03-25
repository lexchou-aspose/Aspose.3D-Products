﻿---
title: Convertir DXF a STL a través de Java 
weight: 360
url: /es/java/conversion/dxf-to-stl/ 
description: Ejemplo de Java código de conversión para DXF formato a STL archivo. Utilice este código de ejemplo para convertir DXF a STL dentro de cualquier aplicación basada en Web o Escritorio Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir DXF a STL a través de Java" h2="Conversión de DXF a STL mediante Java biblioteca sin software de modelado de 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir DXF a STL usando Java" %}}

 Para representar DXF a STL, usaremos
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API que es una plataforma de conversión de API for Java rica en funciones, potente y fácil de usar. Puede descargar su última versión directamente desde
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 E instálelo dentro de su proyecto basado en Maven agregando las siguientes configuraciones al pom.xml.

{{% blocks/products/pf/agp/code-block title="Repositorio" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependencia" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir DXF a STL a través de Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programadores pueden convertir fácilmente DXF archivo a STL en solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargar DXF archivo a través del constructor de la clase Scene1. Crear una instancia de StlSaveOptions1. Establecer STL propiedades específicas para la conversión avanzada1. Call Scene salvar método1. Pase la ruta de salida con STL extensión de archivo y objeto de StlSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de conversión Java, asegúrese de que tiene los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con Java Entorno de tiempo de ejecución para aplicaciones JSP/JSF y aplicaciones de escritorio.- Obtenga la última versión de Aspose.3D for Java directamente de Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DXF a STL Java Código fuente de conversión" offSpacer="" %}}

```cs
// Cargar el DXF en un objeto de Escena 
Scene document = new Scene("template.dxf");
// Crear una instancia de StlSaveOptions 
StlSaveOptions options = new StlSaveOptions();
// Guardar DXF como STL 
document.save("output.stl", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="DXF a STL Demos en vivo de conversión" sectionDescription="[Convertir DXF a STL](https://products.aspose.app/3d/conversion/dxf-to-stl) Ahora mismo visitando nuestro sitio web Live Demos. La demostración en vivo tiene los siguientes beneficios" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su DXF archivo, se convertirá instantáneamente a STL." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá el enlace de descarga." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Biblioteca de manipulación de escenas" %}}

 Aspose.3D es CAD y Gameware API para cargar, modificar y convertir 3D archivos. API es independiente y no requiere ningún 3D software de modelado o renderizado. Uno puede usar fácilmente API para Discreet3DS, WavefrontOBJ, STL (ASCII, Binario), Universal3D, FBX (ASCII, Binario), Collada, glTF, PLY, GLB, DirectX y más formatos. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}

DXF, Formato de intercambio de dibujos o Formato de intercambio de dibujos es una representación de datos etiquetada del archivo de dibujo de AutoCAD. Cada elemento del archivo tiene un número entero de prefijo llamado código de grupo. Este código de grupo representa en realidad el elemento que sigue e indica el significado de un elemento de datos para un tipo de objeto dado. DXF permite representar casi toda la información especificada por el usuario en un archivo de dibujo. El formato de archivo DXF fue desarrollado por Autodesk como CAD formato de archivo de datos para la interoperabilidad de datos entre AutoCAD y otras aplicaciones. Por lo tanto, los datos se pueden importar de otros formatos a DXF a AutoCAD según las especificaciones de interoperabilidad del formato de archivo DXF.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}

STL, abreviatura de estereolitrografía, es un formato de archivo intercambiable que representa la geometría de superficie tridimensional. El formato de archivo encuentra su uso en varios campos, como la creación rápida de prototipos, la impresión 3D y la fabricación asistida por computadora. Representa una superficie como una serie de pequeños triángulos, conocidos como facetas, donde cada faceta se describe mediante una dirección perpendicular y tres puntos que representan los vértices del triángulo. Las aplicaciones utilizan datos resultantes para determinar la sección transversal de la forma 3D que construirá el fabricante. No hay información disponible en el formato de archivo STL para la representación del color, la textura u otros atributos comunes del modelo CAD.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones soportadas" subTitle="También puede convertir DXF en muchos otros formatos de archivo, incluidos algunos que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-3ds/" name="DXF A 3DS" description="3D Malla DOS de estudio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-amf/" name="DXF A AMF" description="Formato de fabricación aditiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ase/" name="DXF A ASE" description="Archivo de animación 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-dae/" name="DXF A DAE" description="Intercambio de activos digitales" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-fbx/" name="DXF A FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-gltf/" name="DXF A GLTF" description="Formato de transmisión GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-html/" name="DXF A HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-obj/" name="DXF A OBJ" description="3D Formato de archivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ply/" name="DXF A PLY" description="Formato de archivo Polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-rvm/" name="DXF A RVM" description="Modelo de diseño de planta AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-u3d/" name="DXF A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}