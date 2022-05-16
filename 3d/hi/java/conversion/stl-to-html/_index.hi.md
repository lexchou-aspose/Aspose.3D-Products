﻿---
title: Java के माध्यम से STL को HTML में बदलें 
weight: 3490
url: /hi/java/conversion/stl-to-html/ 
description: STL प्रारूप से HTML फ़ाइल के लिए नमूना Java रूपांतरण कोड। किसी भी वेब या डेस्कटॉप Java आधारित एप्लिकेशन में STL को HTML में बदलने के लिए इस उदाहरण कोड का उपयोग करें।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java के माध्यम से STL को HTML में बदलें" h2="बिना किसी 3D मॉडलिंग सॉफ़्टवेयर के Java लाइब्रेरी का उपयोग करके STL से HTML रूपांतरण।" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="STL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके STL को HTML में कैसे बदलें" %}}

 STL से HTML को रेंडर करने के लिए, हम उपयोग करेंगे
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API जो एक सुविधा संपन्न, शक्तिशाली और उपयोग में आसान रूपांतरण API for Java प्लेटफॉर्म है। आप इसका नवीनतम संस्करण सीधे से डाउनलोड कर सकते हैं
 [मावेना](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 और pom.xml में निम्नलिखित कॉन्फ़िगरेशन जोड़कर इसे अपने मावेन-आधारित प्रोजेक्ट में स्थापित करें।

{{% blocks/products/pf/agp/code-block title="कोष" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="निर्भरता" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Java के माध्यम से STL को HTML में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 कोड की कुछ ही पंक्तियों में Java प्रोग्रामर आसानी से STL फ़ाइल को HTML में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें STL फ़ाइल1. HtmlSaveOptions का एक उदाहरण बनाएं1. उन्नत रूपांतरण के लिए HTML विशिष्ट गुण सेट करें1. कॉल सीन.सेव मेथड1. HTML फ़ाइल एक्सटेंशन और HtmlSaveOptions के ऑब्जेक्ट के साथ आउटपुट पथ पास करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Java रूपांतरण कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या एक संगत OS जिसमें Java JSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए रनटाइम परिवेश है।- मावेन से सीधे Aspose.3D for Java का नवीनतम संस्करण प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="STL से HTML Java रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// सीन के ऑब्जेक्ट में STL लोड करें 
Scene document = new Scene("template.stl");
// HtmlSaveOptions का एक उदाहरण बनाएं 
Html5SaveOptions options = new Html5SaveOptions();
// STL को HTML के रूप में सहेजें 
document.save("output.html", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="STL से HTML रूपांतरण लाइव प्रदर्शन" sectionDescription="[STL को HTML में बदलें](https://products.aspose.app/3d/conversion/stl-to-html) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी STL फ़ाइल अपलोड करें, यह तुरंत HTML में परिवर्तित हो जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D सीन मैनिपुलेशन लाइब्रेरी" %}}

 Aspose.3D एक CAD और गेमवेयर API है जो 3D फाइलों को लोड, संशोधित और परिवर्तित करता है। API एक स्टैंडअलोन है और इसके लिए किसी भी 3D मॉडलिंग या रेंडरिंग सॉफ़्टवेयर की आवश्यकता नहीं है। Discreet3DS, WavefrontOBJ, STL (ASCII, बाइनरी), Universal3D, FBX (ASCII, बाइनरी), Collada, glTF, PLY, के लिए कोई आसानी से API का उपयोग कर सकता है। GLB, DirectX और अधिक प्रारूप। 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}

STL, स्टीरियोलिथोग्राफी के लिए संक्षिप्त नाम, एक विनिमेय फ़ाइल स्वरूप है जो 3-आयामी सतह ज्यामिति का प्रतिनिधित्व करता है। फ़ाइल प्रारूप कई क्षेत्रों में इसका उपयोग पाता है जैसे कि रैपिड प्रोटोटाइप, 3D प्रिंटिंग और कंप्यूटर-एडेड मैन्युफैक्चरिंग। यह एक सतह को छोटे त्रिभुजों की एक श्रृंखला के रूप में दर्शाता है, जिसे पहलू के रूप में जाना जाता है, जहां प्रत्येक पहलू को लंबवत दिशा और त्रिभुज के शिखर का प्रतिनिधित्व करने वाले तीन बिंदुओं द्वारा वर्णित किया जाता है। परिणामी डेटा का उपयोग अनुप्रयोगों द्वारा फैबर द्वारा बनाए जाने वाले 3D आकार के क्रॉस सेक्शन को निर्धारित करने के लिए किया जाता है। रंग, बनावट या अन्य सामान्य CAD मॉडल विशेषताओं के प्रतिनिधित्व के लिए STL फ़ाइल स्वरूप में कोई जानकारी उपलब्ध नहीं है।


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (हाइपर टेक्स्ट मार्कअप लैंग्वेज) ब्राउज़र में प्रदर्शन के लिए बनाए गए वेब पेजों का एक्सटेंशन है। वेब की भाषा के रूप में जाना जाता है, HTML वेब पेजों के हिस्से के रूप में प्रदर्शित होने वाली नई सूचना आवश्यकताओं की आवश्यकताओं के साथ विकसित हुआ है। नवीनतम संस्करण को HTML 5 के रूप में जाना जाता है जो भाषा के साथ काम करने के लिए बहुत अधिक लचीलापन देता है। HTML पृष्ठ या तो सर्वर से प्राप्त होते हैं, जहां इन्हें होस्ट किया जाता है, या स्थानीय सिस्टम से भी लोड किया जा सकता है। प्रत्येक HTML पृष्ठ HTML तत्वों से बना है जैसे कि प्रपत्र, पाठ, चित्र, एनिमेशन, लिंक, आदि। इन तत्वों को टैग द्वारा दर्शाया जाता है जैसे कि img, a, p और कई अन्य जहां प्रत्येक टैग का प्रारंभ और अंत होता है . यह समग्र लेआउट प्रतिनिधित्व के लिए स्क्रिप्टिंग भाषाओं जैसे जावास्क्रिप्ट और स्टाइल शीट्स (सीएसएस) में लिखे गए अनुप्रयोगों को भी एम्बेड कर सकता है।


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप STL को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-3ds/" name="STL से 3DS" description="3D स्टूडियो डॉस मेश" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-amf/" name="STL से AMF" description="योजक विनिर्माण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-ase/" name="STL से ASE" description="2डी एनिमेशन फाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-dae/" name="STL से DAE" description="डिजिटल एसेट एक्सचेंज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-fbx/" name="STL से FBX" description="3D प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-gltf/" name="STL से GLTF" description="जीएल ट्रांसमिशन प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-obj/" name="STL से OBJ" description="3D फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-ply/" name="STL से PLY" description="बहुभुज फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-rvm/" name="STL से RVM" description="अवेवा प्लांट डिजाइन मॉडल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/stl-to-u3d/" name="STL से U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}