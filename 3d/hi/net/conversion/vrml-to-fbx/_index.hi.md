﻿---
title: C# के माध्यम से VRML को FBX में बदलें 
weight: 3470
url: /hi/net/conversion/vrml-to-fbx/ 
description: VRML से FBX C# रूपांतरण के लिए नमूना कोड। बैच VRML फ़ाइलों के लिए FBX VB.NET, Asp.NET या किसी .NET आधारित एप्लिकेशन में रूपांतरण के लिए API उदाहरण कोड का उपयोग करें।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C# के माध्यम से VRML को FBX में बदलें" h2="बिना किसी 3D मॉडलिंग और रेंडरिंग सॉफ़्टवेयर के VRML को FBX के रूप में प्रस्तुत करें।" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="VRML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# का उपयोग करके VRML को FBX में कैसे बदलें" %}}

 VRML को FBX में बदलने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="C# के माध्यम से VRML को FBX में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 कोड की कुछ ही पंक्तियों में .NET प्रोग्रामर आसानी से VRML फ़ाइलों को FBX में लोड और परिवर्तित कर सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें VRML फ़ाइल1. FbxSaveOptions का एक उदाहरण बनाएं1. उन्नत रूपांतरण के लिए FBX विशिष्ट गुण सेट करें1. दृश्य को कॉल करें। विधि सहेजें1. FBX फ़ाइल एक्सटेंशन और FbxSaveOptions के ऑब्जेक्ट के साथ आउटपुट पथ पास करें1. परिणामी FBX फ़ाइल को निर्दिष्ट पथ पर जांचें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 .NET रूपांतरण कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या .NET Framework, .NET Core, Mono के साथ संगत OS।- माइक्रोसॉफ्ट विजुअल स्टूडियो जैसे विकास पर्यावरण।- Aspose.3D for .NET DLL आपके प्रोजेक्ट में संदर्भित है।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="यह नमूना कोड VRML से FBX C# रूपांतरण दिखाता है" offSpacer="" %}}

```cs
// सीन के ऑब्जेक्ट में VRML लोड करें 
var document = new Aspose.ThreeD.Scene("template.vrml");
// FbxSaveOptions का एक उदाहरण बनाएं 
var options = new Aspose.ThreeD.Formats.FbxSaveOptions();
// VRML को FBX के रूप में सहेजें 
document.Save("output.fbx", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="VRML को FBX में बदलने के लिए निःशुल्क ऐप" sectionDescription="इसके लिए हमारे लाइव डेमो देखें [VRML से FBX रूपांतरण](https://products.aspose.app/3d/conversion/vrml-to-fbx) निम्नलिखित लाभों के साथ।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" कुछ भी डाउनलोड या सेटअप करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी VRML फ़ाइल अपलोड करें और \"कन्वर्ट\" बटन दबाएं।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको परिणामी FBX फ़ाइल के लिए तुरंत डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 बिना किसी मॉडलिंग और रेंडरिंग सॉफ्टवेयर के 3D फाइलों में हेरफेर करने के लिए एक 3D फाइल प्रोसेसिंग लाइब्रेरी। 3D API Discreet3DS, WavefrontOBJ, FBX (ASCII, बाइनरी), STL (ASCII, बाइनरी), Universal3D, Collada, glTF, GLB, का समर्थन करता है। PLY, DirectX, Google Draco फ़ाइल स्वरूप और बहुत कुछ। डेवलपर 3D दस्तावेज़ स्वरूपों के सार को आसानी से बना सकते हैं, पढ़ सकते हैं, रूपांतरित कर सकते हैं, संशोधित कर सकते हैं और नियंत्रित कर सकते हैं।



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="VRML" readMoreLink="https://docs.fileformat.com/3d/vrml/" >}}
वर्चुअल रियलिटी मॉडलिंग लैंग्वेज (VRML) वर्ल्ड वाइड वेब (www) पर इंटरैक्टिव 3D विश्व वस्तुओं के प्रतिनिधित्व के लिए एक फ़ाइल प्रारूप है। यह चित्रण, परिभाषा और आभासी वास्तविकता प्रस्तुतियों जैसे जटिल दृश्यों के त्रि-आयामी प्रतिनिधित्व बनाने में इसका उपयोग पाता है। प्रारूप को X3D द्वारा अधिगृहीत कर दिया गया है। कई 3D मॉडलिंग अनुप्रयोग वस्तुओं और दृश्यों को VRML प्रारूप में सहेज सकते हैं।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="fbx" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, फिल्मबॉक्स, एक लोकप्रिय 3D फ़ाइल स्वरूप है जिसे मूल रूप से मोशनबिल्डर के लिए केदारा द्वारा विकसित किया गया था। इसे ऑटोडेस्क इंक द्वारा 2006 में अधिग्रहित किया गया था और अब यह मुख्य 3D एक्सचेंज प्रारूपों में से एक है जैसा कि कई 3D टूल द्वारा उपयोग किया जाता है। FBX बाइनरी और एएससीआईआई फ़ाइल स्वरूप दोनों में उपलब्ध है। प्रारूप को डिजिटल सामग्री निर्माण अनुप्रयोगों के बीच अंतःक्रियाशीलता प्रदान करने के लिए स्थापित किया गया था। FBX फ़ाइल स्वरूप से/में रूपांतरण के लिए कई उपकरण उपलब्ध हैं।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप VRML को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-3ds/" name="VRML से 3DS" description="3D स्टूडियो डॉस मेश" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-amf/" name="VRML से AMF" description="योजक विनिर्माण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-dae/" name="VRML से DAE" description="डिजिटल एसेट एक्सचेंज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-html/" name="VRML से HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-obj/" name="VRML से OBJ" description="3D फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-pdf/" name="VRML से PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-ply/" name="VRML से PLY" description="बहुभुज फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-rvm/" name="VRML से RVM" description="अवेवा प्लांट डिजाइन मॉडल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-stl/" name="VRML से STL" description="विनिमेय 3D भूतल ज्यामिति" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/vrml-to-u3d/" name="VRML से U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}