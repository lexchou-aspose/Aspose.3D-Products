﻿---
title: Extraiga activos de GLTF formatos de archivo a través de .NET 
weight: 830
url: /es/net/extractor/gltf/ 
description: Código fuente de C# para cargar, renderizar y agregar activos extraídos de GLTF documentos en .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Extraer activos de GLTF a través de C#" h2="Cree sus propias aplicaciones .NET para extraer recursos de archivos GLTF mediante las API del lado del servidor." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo extraer activos del archivo GLTF usando C#" %}}

 Para extraer activos del archivo GLTF, usaremos
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, que es una plataforma API para C# rica en funciones, potente y fácil de usar para usar con recursos de extracción. Abierto
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 administrador de paquetes, busque
 **Aspose.3D** 
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Comando de la consola del Administrador de paquetes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para extraer activos de GLTF a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D facilita a los desarrolladores la extracción de activos del archivo GLTF con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

- Cargue el archivo GLTF a través del constructor de la clase Escena- Crear objeto de formato de archivo zip como formato de archivo de salida- Crear clase de archivo y manejar la clase de activo de extracción- Llame al método Extract y guarde el archivo
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET es compatible con todos los principales sistemas operativos. Solo asegúrese de tener los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core, Mono- Entorno de desarrollo como Microsoft Visual Studio- Aspose.3D for .NET referenciado en su proyecto
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código C# para extraer recursos de GLTF" offSpacer="" %}}

```cs

//Archivos de origen que necesitan extraer activos
string file = "template.gltf";
Scene scene = new Scene(file);  

//La salida está en un formato de archivo comprimido y Directorio representa el nombre de una carpeta existente
var zipOutput = Path.Combine("Directory", "OutputFile.zip");
using var output = new FileStream(zipOutput, FileMode.Create);
using var za = new Zip(output);

//Llame al método Extract para realizar operaciones de extracción de activos
Extract(scene,za,true);

//Método de extracción invocable, la textura del parámetro indica: si se extrae la textura
private void Extract(Scene scene, Zip za,bool texture)
{
    var extractor = new Extractor(za,texture);
    extractor.Extract(scene);
}

//Crear una clase de procesamiento de archivos comprimidos
class Zip : IDisposable
{
    private ZipArchive archive;
    private HashSet<string> entries = new HashSet<string>();

    public Zip(Stream stream)
    {
        archive = new ZipArchive(stream, ZipArchiveMode.Create);
    }
    public void Dispose()
    {
        archive.Dispose();
    }

    public void Add(string fileName, byte[] content, bool enableCompression)
    {
        var entryName = PickName(fileName);
        var compressionLevel = enableCompression ? CompressionLevel.Fastest : CompressionLevel.NoCompression;
        var entry = archive.CreateEntry(entryName, compressionLevel);
        using var stream = entry.Open();
        stream.Write(content, 0, content.Length);
    }
    
    private string PickName(string fileName)
    {
        if (!entries.Contains(fileName))
        {
            entries.Add(fileName);
            return fileName;
        }
        var baseName = Path.GetFileNameWithoutExtension(fileName);
        var ext = Path.GetExtension(fileName);
        for (var idx = 2; ; idx++)
        {
            var newName = baseName + "_" + idx;
            if (!string.IsNullOrEmpty(ext))
                newName += ext;
            if (entries.Contains(newName))
                continue;
            entries.Add(newName);
            return newName;
        }
    }
}

//Crear una clase de procesamiento de extracción de activos
class Extractor
{
    private Zip zip;
    private bool texture;
    HashSet<A3DObject> visited = new HashSet<A3DObject>();
    public Extractor(Zip zip,bool texture)
    {
        this.zip = zip;
        this.texture = texture;
    }

    private bool CanVisit(A3DObject obj)
    {
        if (visited.Contains(obj))
            return false;
        visited.Add(obj);
        return true;
    }
    public void Extract(Scene scene)
    {
        if (scene.Library != null && scene.Library.Count > 0)
        {
            foreach (var obj in scene.Library)
            {
                Visit(obj);
            }
        }
        VisitNode(scene.RootNode);
    }
    private void VisitNode(Node node)
    {
        if (!CanVisit(node))
            return;
        if (texture)
        {
            foreach (var mat in node.Materials)
            {
                VisitMaterial(mat);
            }
        }

        foreach (var entity in node.Entities)
        {
            if (entity is Mesh)
                Save((Mesh)entity, node.Name);
        }
        
        foreach (var child in node.ChildNodes)
        {
            VisitNode(child);
        }
    }
    private void VisitMaterial(Material mat)
    {
        if (!CanVisit(mat))
            return;
        if (!texture)
            return;
        foreach (var tslot in mat)
        {
            if (tslot.Texture is Texture)
            {
                Save((Texture)tslot.Texture);
            }
        }
    }
    private void Visit(A3DObject obj)
    {
        if (texture && obj is Texture)
        {
            Save((Texture)obj);
        }
        else if (obj is Mesh)
        {
            Save((Mesh)obj, null);
        }
        else if (obj is Node)
        {
            VisitNode((Node)obj);
        }
    }
    private void Save(Mesh mesh, string? nodeName)
    {
        if (!CanVisit(mesh))
            return;
        Scene scene = new Scene(mesh);
        using (var ms = new MemoryStream())
        {
            scene.Save(ms, FileFormat.FBX7400ASCII);
            var name = nodeName;
            if (string.IsNullOrEmpty(name))
                name = mesh.Name;
            if (string.IsNullOrEmpty(name))
                name = "mesh";
            var ext = ".fbx";
            zip.Add(name + ext, ms.ToArray(), true);
        }
    }
    private void Save(Texture tex)
    {
        if (tex.Content == null || !CanVisit(tex))
            return;
        var fileName = tex.FileName != null ? Path.GetFileName(tex.FileName) : null;
        zip.Add(fileName, tex.Content, false);
    }
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Acerca de Aspose.3D for .NET API" %}}

 Aspose.3D es un CAD y Gameware API para cargar, modificar y convertir archivos 3D. API es independiente y no requiere ningún 3D software de modelado o renderizado. Uno puede usar fácilmente API para Discreet3DS, WavefrontOBJ, STL (ASCII, binario), Universal3D, FBX (ASCII, binario), Collada, glTF, PLY, GLB, DirectX y más formatos. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicación gratuita para extraer activos de GLTF" sectionDescription="Consulte nuestras demostraciones en vivo para [Extractor GLTF](https://products.aspose.app/3d/extractor/gltf) con los siguientes beneficios." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir o compilar código" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue el archivo GLTF y presione el botón \"Extraer\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Descargue el archivo GLTF desde el enlace, si es necesario" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (formato de transmisión GL) es un formato de archivo 3D que almacena información del modelo 3D en formato JSON. El uso de JSON minimiza tanto el tamaño de los activos 3D como el procesamiento en tiempo de ejecución necesario para desempaquetar y usar esos activos. Fue adoptado para la transmisión y carga eficiente de 3D escenas y modelos por aplicaciones.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otra aplicación compatible para extraer activos de formatos" subTitle="Con C#, también se pueden extraer activos de muchos otros formatos de archivo, incluidos." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/3mf/" name="3MF" description="3D formato de fabricación" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/amf/" name="AMF" description="Formato de fabricación aditiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/ase/" name="ASE" description="Archivo de animación 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/dae/" name="DAE" description="Intercambio de activos digitales" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/dxf/" name="DXF" description="Formato de intercambio de dibujos" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/fbx/" name="FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/glb/" name="GLB" description="3D Representación binaria de archivos" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/3ds/" name="3DS" description="3D Formato de archivo de malla de Studio" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/jt/" name="JT" description="Archivo de teselado de Júpiter" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/obj/" name="OBJ" description="3D formato de archivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/ply/" name="PLY" description="Formato de archivo de polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/rvm/" name="RVM" description="Modelo de diseño de planta de AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/stl/" name="STL" description="Geometría de superficie intercambiable 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/vrml/" name="VRML" description="Lenguaje de modelado de realidad virtual" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/x/" name="X" description="Imagen del modelo de DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/usd/" name="USD" description="Descripción de la escena universal" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/usdz/" name="USDZ" description="Universal Escena Descripción Zip Archivo" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}