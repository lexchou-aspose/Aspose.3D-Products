﻿---
title: .NET के माध्यम से PDF फ़ाइल स्वरूपों से एसेट निकालें 
weight: 830
url: /hi/net/extractor/pdf/ 
description: .NET फ्रेमवर्क, .NET कोर, Mono पर PDF दस्तावेज़ों से एक्सट्रैक्ट एसेट लोड करने, रेंडर करने और जोड़ने के लिए C# स्रोत कोड।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="PDF से C# के माध्यम से संपत्तियां निकालें" h2="सर्वर-साइड API का उपयोग करके PDF फ़ाइलों से एसेट निकालने के लिए अपने स्वयं के .NET ऐप्स बनाएं।" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="PDF फ़ाइल का उपयोग करके C# से एसेट कैसे निकालें" %}}

 PDF फ़ाइल से एसेट निकालने के लिए, हम उपयोग करेंगे
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान API है जो C# प्लेटफॉर्म के लिए एक्सट्रैक्ट एसेट के साथ उपयोग किया जाता है। खुला हुआ
 [नुगेट](https://www.nuget.org/packages/aspose.3d) 
 पैकेज मैनेजर, खोजें
 ***** 
 और स्थापित करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="पैकेज मैनेजर कंसोल कमांड" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="PDF से C# के माध्यम से संपत्ति निकालने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D केवल कोड की कुछ पंक्तियों के साथ PDF फ़ाइल से एसेट निकालना डेवलपर के लिए आसान बनाता है.

{{% /blocks/products/pf/agp/text %}}

- सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें PDF फ़ाइल- आउटपुट फ़ाइल स्वरूप के रूप में ज़िप फ़ाइल स्वरूप वस्तु बनाएँ- आर्काइव क्लास बनाएं और एक्सट्रैक्ट एसेट क्लास को हैंडल करें- एक्सट्रैक्ट मेथड को कॉल करें और फाइल को सेव करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET सभी प्रमुख ऑपरेटिंग सिस्टम पर समर्थित है। बस सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Mono के साथ संगत OS- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास का माहौल- Aspose.3D for .NET आपके प्रोजेक्ट में संदर्भित
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# कोड PDF से संपत्ति निकालने के लिए" offSpacer="" %}}

```cs

//स्रोत फ़ाइलें जिन्हें संपत्ति निकालने की आवश्यकता होती है
var scenes = FileFormat.PDF.ExtractScene("template.pdf");
for(int i = 0; i < scenes.Count; i++)
{
    scenes[i].Save($"scene-{i}.fbx", FileFormat.FBX7400ASCII);
}


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="लगभग Aspose.3D for .NET API" %}}

 Aspose.3D एक CAD और गेमवेयर API है जो 3D फाइलों को लोड, संशोधित और परिवर्तित करता है। API एक स्टैंडअलोन है और इसके लिए किसी भी 3D मॉडलिंग या रेंडरिंग सॉफ़्टवेयर की आवश्यकता नहीं है। Discreet3DS, WavefrontOBJ, STL (ASCII, बाइनरी), Universal3D, FBX (ASCII, बाइनरी), Collada, glTF, PLY, के लिए कोई आसानी से API का उपयोग कर सकता है। GLB, DirectX और अधिक प्रारूप। 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="PDF से संपत्ति निकालने के लिए निःशुल्क ऐप" sectionDescription="हमारे लाइव डेमो की जांच करें [निकालने वाला PDF](https://products.aspose.app/3d/extractor/pdf) निम्नलिखित लाभों के साथ।" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोड लिखने या संकलित करने की आवश्यकता नहीं है" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस PDF फ़ाइल अपलोड करें और \"निकालें\" बटन दबाएं" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" यदि आवश्यक हो, तो लिंक से PDF फ़ाइल डाउनलोड करें" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" >}}
पोर्टेबल दस्तावेज़ प्रारूप (PDF) 1990 के दशक में Adobe द्वारा बनाया गया एक प्रकार का दस्तावेज़ है। इस फाइल फॉर्मेट का उद्देश्य दस्तावेजों और अन्य संदर्भ सामग्री के प्रतिनिधित्व के लिए एक मानक को एक प्रारूप में पेश करना था जो एप्लिकेशन सॉफ्टवेयर, हार्डवेयर और साथ ही ऑपरेटिंग सिस्टम से स्वतंत्र हो। PDF फाइलें एडोब एक्रोबेट रीडर/राइटर में और साथ ही क्रोम, सफारी, फ़ायरफ़ॉक्स जैसे अधिकांश आधुनिक ब्राउज़रों में एक्सटेंशन/प्लग-इन के माध्यम से खोली जा सकती हैं।


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="प्रारूपों से संपत्ति निकालने के लिए अन्य समर्थित ऐप" subTitle="C# का उपयोग करके, कोई भी व्यक्ति सहित कई अन्य फ़ाइल स्वरूपों से संपत्तियां निकाल सकता है।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/3mf/" name="3MF" description="3D निर्माण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/amf/" name="AMF" description="योजक विनिर्माण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/ase/" name="ASE" description="2डी एनिमेशन फाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/dae/" name="DAE" description="डिजिटल एसेट एक्सचेंज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/dxf/" name="DXF" description="ड्राइंग इंटरचेंज प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/fbx/" name="FBX" description="3D प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/glb/" name="GLB" description="3D फ़ाइल बाइनरी प्रतिनिधित्व" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/gltf/" name="GLTF" description="जीएल ट्रांसमिशन प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/jt/" name="JT" description="बृहस्पति टेसेलेशन फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/obj/" name="OBJ" description="3D फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/ply/" name="PLY" description="बहुभुज फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/3ds/" name="3DS" description="3D स्टूडियो मेश फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/rvm/" name="RVM" description="अवेवा प्लांट डिजाइन मॉडल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/stl/" name="STL" description="विनिमेय 3D भूतल ज्यामिति" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/vrml/" name="VRML" description="आभासी वास्तविकता मॉडलिंग भाषा" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/x/" name="एक्स" description="DirectX मॉडल छवि" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/usd/" name="USD" description="यूनिवर्सल सीन विवरण" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/extractor/usdz/" name="USDZ" description="यूनिवर्सल सीन विवरण जिप आर्काइव" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}