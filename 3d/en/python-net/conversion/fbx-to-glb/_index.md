---
title: Convert FBX to GLB via Python 
url: /python-net/conversion/fbx-to-glb/ 
description: Sample code for FBX to GLB Python conversion. Use API example code for batch FBX files to GLB conversion within VB.NET, Asp.NET or any .NET based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert FBX to GLB via Python" h2="Render FBX as GLB without any 3D modeling and rendering software." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Python via .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="/3d/aspose_3d-for-python-via-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/python-net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/python-net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert FBX to GLB Using Python" %}}

 In order to convert FBX to GLB, we’ll use
 [Aspose.3D for Python via .NET](https://products.aspose.com/3d/python-net) 
 API which is a feature-rich, powerful and easy to use document manipulation and conversion API for Python. Open
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 package manager, search for
 Aspose.3D 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command line" offSpacer="true" %}}

```cs

pip install aspose-3d

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Convert FBX to GLB via Python" %}}

{{% blocks/products/pf/agp/text %}}

 Python programmers can easily load & convert FBX files to GLB in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

1.  Load FBX file via the from_file of Scene class
1.  Create an instance of AmfSaveOptions
1.  Set GLB specific properties for advanced conversion
1.  Call the Scene.save method
1.  Pass the output path with GLB file extension & object of StlSaveOptions
1.  Check resultant GLB file at specified path

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Before running the Python conversion code, make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or Linux based OS.
-  Python 3.5 or later.
-  Aspose.3D for Python referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="This sample code shows FBX to GLB Python Conversion" offSpacer="" %}}

```cs
# load the FBX in an object of Scene 
document = aspose.threed.Scene.from_file("template.fbx");
# create an instance of GltfSaveOptions 
options = aspose.threed.formats.GltfSaveOptions(FileContentType.Binary);
# save FBX as a GLB 
document.save("output.glb", options); 

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox-app sectionTitle="Free App to Convert FBX to GLB" sectionDescription="Check our live demos for [FBX to GLB conversion](https://products.aspose.app/3d/conversion/fbx-to-glb) with following benefits." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your FBX file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant GLB file." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 A 3D File Processing Library to manipulate 3D files without any modeling and rendering software. The 3D API supports Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), GLB (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco file formats and more. Developers can create, read, convert, modify and control the substance of 3D document formats easily.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox, is a popular 3D file format that was originally developed by Kaydara for MotionBuilder. It was acquired by Autodesk Inc in 2006 and is now one of the main 3D exchange formats as used by many 3D tools. FBX is available in both binary and ASCII file format. The format was established to provided interoperability between digital content creation applications. There are many tools available for conversion from/to FBX file format.

        {{< /blocks/products/pf/agp/about-file-text >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}
GLB is the binary file format representation of 3D models saved in the GL Transmission Format (glTF). Information about 3D models such as node hierarchy, cameras, materials, animations and meshes in binary format. This binary format stores the glTF asset (JSON, .bin and images) in a binary blob. It also avoids the issue of increase in file size which happens in case of glTF. GLB file format results in compact file sizes, fast loading, complete 3D scene representation, and extensibility for further development. The format uses model/gltf-binary as MIME type.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}