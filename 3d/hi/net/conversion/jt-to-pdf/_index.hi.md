﻿---
title: C# के माध्यम से JT को PDF में बदलें 
weight: 2910
url: /hi/net/conversion/jt-to-pdf/ 
description: JT से PDF C# रूपांतरण के लिए नमूना कोड। बैच JT फ़ाइलों के लिए PDF VB.NET, Asp.NET या किसी .NET आधारित एप्लिकेशन में रूपांतरण के लिए API उदाहरण कोड का उपयोग करें।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# के माध्यम से JT को PDF में बदलें" h2="बिना किसी 3D मॉडलिंग और रेंडरिंग सॉफ़्टवेयर के JT को PDF के रूप में प्रस्तुत करें।" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके JT को PDF में कैसे बदलें" %}}

 JT को PDF में बदलने के लिए, हम उपयोग करेंगे
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API जो C# प्लेटफॉर्म के लिए एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ हेरफेर और रूपांतरण API है। खुला हुआ
 [नुगेट](https://www.nuget.org/packages/aspose.3d) 
 पैकेज मैनेजर, खोजें
 Aspose.3D 
 और स्थापित करें। आप पैकेज मैनेजर कंसोल से निम्न कमांड का भी उपयोग कर सकते हैं।

{{% blocks/products/pf/agp/code-block title="पैकेज मैनेजर कंसोल कमांड" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से JT को PDF में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 कोड की कुछ ही पंक्तियों में .NET प्रोग्रामर आसानी से JT फ़ाइलों को PDF में लोड और परिवर्तित कर सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें JT फ़ाइल1. PdfSaveOptions का एक उदाहरण बनाएं1. उन्नत रूपांतरण के लिए PDF विशिष्ट गुण सेट करें1. दृश्य को कॉल करें। विधि सहेजें1. आउटपुट पथ को PDF फ़ाइल एक्सटेंशन और PdfSaveOptions के ऑब्जेक्ट के साथ पास करें1. परिणामी PDF फ़ाइल को निर्दिष्ट पथ पर जांचें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 .NET रूपांतरण कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Mono के साथ संगत OS।- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास पर्यावरण।- Aspose.3D for .NET DLL आपके प्रोजेक्ट में संदर्भित है।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="यह नमूना कोड JT से PDF C# रूपांतरण दिखाता है" offSpacer="" %}}

```cs
// सीन के ऑब्जेक्ट में JT लोड करें 
var document = new Aspose.ThreeD.Scene("template.jt");
// PdfSaveOptions का एक उदाहरण बनाएं 
var options = new Aspose.ThreeD.Formats.PdfSaveOptions();
// JT को PDF के रूप में सहेजें 
document.Save("output.pdf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="JT को PDF में बदलने के लिए निःशुल्क ऐप" sectionDescription="इसके लिए हमारे लाइव डेमो देखें [JT से PDF रूपांतरण](https://products.aspose.app/3d/conversion/jt-to-pdf) निम्नलिखित लाभों के साथ।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी JT फ़ाइल अपलोड करें और \"कन्वर्ट\" बटन दबाएं।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको परिणामी PDF फ़ाइल के लिए तुरंत डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 बिना किसी मॉडलिंग और रेंडरिंग सॉफ्टवेयर के 3D फाइलों में हेरफेर करने के लिए एक 3D फाइल प्रोसेसिंग लाइब्रेरी। 3D API Discreet3DS, WavefrontOBJ, FBX (ASCII, बाइनरी), STL (ASCII, बाइनरी), Universal3D, Collada, glTF, GLB, का समर्थन करता है। PLY, DirectX, Google Draco फ़ाइल स्वरूप और बहुत कुछ। डेवलपर 3D दस्तावेज़ स्वरूपों के सार को आसानी से बना सकते हैं, पढ़ सकते हैं, रूपांतरित कर सकते हैं, संशोधित कर सकते हैं और नियंत्रित कर सकते हैं।



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JT" readMoreLink="https://docs.fileformat.com/3d/jt/" >}}
JT (बृहस्पति टेसेलेशन) सीमेंस पीएलएम सॉफ्टवेयर द्वारा विकसित एक कुशल, उद्योग-केंद्रित और लचीला आईएसओ-मानकीकृत 3D डेटा प्रारूप है। एयरोस्पेस, ऑटोमोटिव उद्योग और भारी उपकरण के यांत्रिक CAD डोमेन अपने सबसे प्रमुख 3D विज़ुअलाइज़ेशन प्रारूप के रूप में JT का उपयोग करते हैं। JT प्रारूप एक दृश्य ग्राफ है जो विशिष्ट विशेषताओं और नोड्स का समर्थन करता है जो कि CAD विशिष्ट हैं। पहलू डेटा (त्रिकोण) को संग्रहीत करने के लिए परिष्कृत संपीड़न तकनीकों का उपयोग किया जाता है। यह प्रारूप दृश्य विशेषताओं, उत्पाद और निर्माण जानकारी (पीएमआई), और मेटाडेटा का समर्थन करने के लिए संरचित है। सामग्री की अतुल्यकालिक स्ट्रीमिंग के लिए एक अच्छा समर्थन है। भारी यांत्रिक उद्योग में, पेशेवर अपने CAD समाधान और उत्पाद जीवनचक्र प्रबंधन (पीएलएम) सॉफ़्टवेयर प्रोग्राम में JT फ़ाइल का उपयोग जटिल वस्तुओं की ज्यामिति की जांच करने के लिए करते हैं।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="pdf" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
पोर्टेबल दस्तावेज़ प्रारूप (PDF) 1990 के दशक में Adobe द्वारा बनाया गया एक प्रकार का दस्तावेज़ है। इस फाइल फॉर्मेट का उद्देश्य दस्तावेजों और अन्य संदर्भ सामग्री के प्रतिनिधित्व के लिए एक मानक को एक प्रारूप में पेश करना था जो एप्लिकेशन सॉफ्टवेयर, हार्डवेयर और साथ ही ऑपरेटिंग सिस्टम से स्वतंत्र हो। PDF फाइलें एडोब एक्रोबेट रीडर/राइटर में और साथ ही क्रोम, सफारी, फ़ायरफ़ॉक्स जैसे अधिकांश आधुनिक ब्राउज़रों में एक्सटेंशन/प्लग-इन के माध्यम से खोली जा सकती हैं। अधिकांश व्यावसायिक रूप से उपलब्ध सॉफ़्टवेयर सूट बिना किसी अतिरिक्त सॉफ़्टवेयर घटक की आवश्यकता के अपने दस्तावेज़ों को PDF फ़ाइल स्वरूप में बदलने की पेशकश करते हैं। इस प्रकार, PDF फ़ाइल प्रारूप में टेक्स्ट, इमेज, हाइपरलिंक, फॉर्म-फ़ील्ड, रिच मीडिया, डिजिटल हस्ताक्षर, अटैचमेंट, मेटाडेटा, भू-स्थानिक विशेषताएं और 3D ऑब्जेक्ट जैसी जानकारी शामिल करने की पूरी क्षमता है जो स्रोत के हिस्से के रूप में बन सकती हैं। दस्तावेज़।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप JT को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-3ds/" name="JT से 3DS" description="3D स्टूडियो डॉस मेश" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-amf/" name="JT से AMF" description="योजक विनिर्माण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-dae/" name="JT से DAE" description="डिजिटल एसेट एक्सचेंज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-fbx/" name="JT से FBX" description="3D प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-html/" name="JT से HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-obj/" name="JT से OBJ" description="3D फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-ply/" name="JT से PLY" description="बहुभुज फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-rvm/" name="JT से RVM" description="अवेवा प्लांट डिजाइन मॉडल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-stl/" name="JT से STL" description="विनिमेय 3D भूतल ज्यामिति" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/jt-to-u3d/" name="JT से U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}