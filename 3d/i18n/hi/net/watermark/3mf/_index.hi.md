﻿---
title: जोड़ने अंधा के लिए वॉटरमार्क 3MF फ़ाइल स्वरूपों के माध्यम से .NET 
weight: 830
url: /hi/net/watermark/3mf/ 
description: C# स्रोत कोड लोड करने के लिए, प्रस्तुत करना और जोड़ने अंधा के लिए वॉटरमार्क 3MF दस्तावेजों पर .NET ढांचे, .NET कोर, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="जोड़ने अंधा के लिए वॉटरमार्क 3MF के माध्यम से C#" h2="अपना स्वयं का निर्माण .NET क्षुधा करने के लिए वॉटरमार्क 3MF फ़ाइलें सर्वर-साइड Api का उपयोग." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="3MF" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3MF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="कैसे करने के लिए के लिए वॉटरमार्क 3MF फ़ाइल का उपयोग C#" %}}

 आदेश में करने के लिए वॉटरमार्क 3MF फ़ाइल, हम 'करूँगा उपयोग
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API एक सुविधा है जो-अमीर, शक्तिशाली और प्रयोग करने में आसान API के लिए C# मंच करने के लिए किसी भी वॉटरमार्क जोड़ने के साथ इस्तेमाल किया जा सकता है है। खुले
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 पैकेज प्रबंधक, खोज के लिए
 **Aspose.3D** 
 और स्थापित है। आप का उपयोग कर सकते निम्नलिखित कमांड से पैकेज प्रबंधक कंसोल.

{{% blocks/products/pf/agp/code-block title="पैकेज प्रबंधक कंसोल कमांड" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="कदम जोड़ने के लिए अंधा के लिए वॉटरमार्क 3MF के माध्यम से C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D डेवलपर्स के लिए यह आसान बनाता है जोड़ने के लिए अंधा के लिए वॉटरमार्क के 3MF के साथ फ़ाइल बस कुछ ही लाइनों के कोड है।

{{% /blocks/products/pf/agp/text %}}

- लोड 3MF फ़ाइल के माध्यम से constructor दृश्य की श्रेणी- जाल की कक्षा प्राप्त Aspose.3D- वॉटरमार्क जोड़ने और पासवर्ड का उपयोग Aspose.3D की EncodeWatermark विधि- कॉल के दृश्य. Save विधि वस्तु के साथ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएँ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है. सिर्फ सुनिश्चित करें कि आपके पास निम्नलिखित distributionname.

{{% /blocks/products/pf/agp/text %}}

- माइक्रोसॉफ्ट विंडोज के साथ या एक संगत ओएस .NET ढांचे, .NET कोर, Mono- विकास वातावरण की तरह माइक्रोसॉफ्ट विजुअल स्टूडियो- Aspose.3D for .NET अपनी परियोजना में संदर्भित
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# कोड जोड़ने के लिए अंधा के लिए वॉटरमार्क 3MF" offSpacer="" %}}

```cs

//के स्रोत फ़ाइल हो करने के लिए की जरूरत है कि watermarked और आउटपुट फ़ाइल के बाद बचत
string file = "template.3mf";
string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

// एक दृश्य के उदाहरण बनाने
Scene scene = new Scene(file);

//वॉटरमार्क जोड़ने और करने के लिए पासवर्ड फ़ाइलें
var numMeshes = 0;
scene.RootNode.Accept((Node node) =>
{
    var mesh = node.GetEntity<Mesh>();
    if (mesh != null)
    {
        numMeshes++;
        mesh = Watermark.EncodeWatermark(mesh, "HelloWorld", "1234");
        if (mesh != null)
        {
            node.Entity = mesh;
        }
    }
    return true;
});

//बचाने के लिए फ़ाइल प्रारूप में आप चाहते हैं
scene.Save(output, FileFormat.FBX7400ASCII);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="के बारे में Aspose.3D for .NET API" %}}

 Aspose.3D है कार्यों के साथ एक CAD और Gameware API लोड करने के लिए, संशोधित करने और कन्वर्ट 3D फ़ाइलें. API एक स्टैंडअलोन और की आवश्यकता नहीं करता है किसी भी किसी भी 3D मॉडलिंग या प्रतिपादन सॉफ्टवेयर है। एक आसानी से उपयोग कर सकते हैं API के लिए Discreet3DS, WavefrontOBJ, STL (ASCII, बाइनरी), Universal3D, FBX (ASCII, बाइनरी), Collada, glTF, PLY, GLB, इंटरनेट और अधिक प्रारूपों। 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

 {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="नि: शुल्क एप्लिकेशन जोड़ने के लिए अंधा के लिए वॉटरमार्क 3MF" sectionDescription="जाँच करने के लिए हमारे जीने क़ौम [वॉटरमार्क 3MF](https://products.aspose.app/3d/watermark/3mf) निम्नलिखित लाभ के साथ." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कोई डाउनलोड करने की आवश्यकता या सेटअप कुछ भी" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई लिखने के लिए या कंपाइल कोड की जरूरत" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" सिर्फ अपलोड 3MF फ़ाइल और मारा \"वॉटरमार्क\" बटन" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" डाउनलोड 3MF फ़ाइल से लिंक, यदि आवश्यक हो तो" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3MF" readMoreLink="https://docs.fileformat.com/3d/3mf/" >}}
3MF, 3D विनिर्माण प्रारूप, रेंडर करने के लिए आवेदन द्वारा प्रयोग किया जाता है 3D वस्तु मॉडल की एक किस्म के लिए अन्य अनुप्रयोगों, प्लेटफार्मों, सेवाओं और प्रिंटर यह सीमाएं से बचने के लिए बनाया गया था और मुद्दों में अन्य 3D फ़ाइल स्वरूपों, की तरह STL, के साथ काम करने के लिए नवीनतम संस्करणों की 3D प्रिंटर 3MF विकसित किया गया है कि एक नई फ़ाइल प्रारूप अपेक्षाकृत है और के द्वारा प्रकाशित 3MF संघ.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित एप्लिकेशन जोड़ने के लिए अंधा के लिए वॉटरमार्क प्रारूपों" subTitle="का उपयोग कर C#, एक के लिए वॉटरमार्क अंधा जोड़ने भी कर सकते हैं कई अन्य फ़ाइल स्वरूपों सहित." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3ds/" name="3DS" description="3D स्टूडियो जाल फ़ाइल प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/amf/" name="AMF" description="Additive विनिर्माण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/ase/" name="ASE" description="2D एनीमेशन फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dae/" name="DAE" description="डिजिटल परिसंपत्ति विनिमय" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dxf/" name="DXF" description="ड्राइंग इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/fbx/" name="FBX" description="3D प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/glb/" name="GLB" description="3D फ़ाइल बाइनरी प्रतिनिधित्व" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/gltf/" name="GLTF" description="जीएल संचरण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/jt/" name="JT" description="बृहस्पति Tessellation फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/obj/" name="OBJ" description="3D फ़ाइल प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/ply/" name="PLY" description="बहुभुज फ़ाइल प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/rvm/" name="RVM" description="AVEVA संयंत्र डिजाइन मॉडल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/stl/" name="STL" description="विनिमेय 3D सतह ज्यामिति" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/vrml/" name="VRML" description="आभासी वास्तविकता मॉडलिंग भाषा" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/x/" name="X" description="इंटरनेट मॉडल छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usd/" name="USD" description="यूनिवर्सल दृश्य विवरण" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usdz/" name="USDZ" description="यूनिवर्सल दृश्य विवरण ज़िप अभिलेख" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}