﻿---
title: Java के माध्यम से DAE को USDZ में बदलें
weight: 530
url: /hi/java/conversion/dae-to-usdz/ 
description: DAE प्रारूप से USDZ फ़ाइल के लिए नमूना Java रूपांतरण कोड। किसी भी वेब या डेस्कटॉप Java आधारित एप्लिकेशन में DAE को USDZ में बदलने के लिए इस उदाहरण कोड का उपयोग करें।
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java के माध्यम से DAE को USDZ में बदलें" h2="बिना किसी 3D मॉडलिंग सॉफ़्टवेयर के Java लाइब्रेरी का उपयोग करके DAE से USDZ रूपांतरण।" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="USDZ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DAE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Java का उपयोग करके DAE को USDZ में कैसे बदलें" %}}

 DAE से USDZ को रेंडर करने के लिए, हम उपयोग करेंगे
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

{{% blocks/products/pf/agp/feature-section-col title="Java के माध्यम से DAE को USDZ में बदलने के चरण" %}}

{{% blocks/products/pf/agp/text %}}

 कोड की कुछ ही पंक्तियों में Java प्रोग्रामर आसानी से DAE फ़ाइल को USDZ में बदल सकते हैं।

{{% /blocks/products/pf/agp/text %}}

1. सीन क्लास के कंस्ट्रक्टर के माध्यम से लोड करें DAE फ़ाइल1. Scene.save विधि को USDZ के प्रारूप के साथ कॉल करें।1. परिणामी USDZ फ़ाइल को निर्दिष्ट पथ पर जांचें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="सिस्टम आवश्यकताएं" %}}

{{% blocks/products/pf/agp/text %}}

 Java रूपांतरण कोड चलाने से पहले, सुनिश्चित करें कि आपके पास निम्नलिखित पूर्वापेक्षाएँ हैं।

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows या एक संगत OS जिसमें Java JSP/JSF अनुप्रयोग और डेस्कटॉप अनुप्रयोगों के लिए रनटाइम परिवेश है।- मावेन से सीधे Aspose.3D for Java का नवीनतम संस्करण प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DAE से USDZ Java रूपांतरण स्रोत कोड" offSpacer="" %}}

```cs
// स्रोत लोड करें Collada DAE फ़ाइल
Scene scene = new Scene("sourceFile.dae");
// 3D दृश्य को USDZ प्रारूप में फ़ाइल में बदलें
scene.save("output.usdz", FileFormat.USDZ)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DAE से USDZ रूपांतरण लाइव प्रदर्शन" sectionDescription="[DAE को USDZ में बदलें](https://products.aspose.app/3d/conversion/dae-to-usdz) अभी हमारी लाइव डेमो वेबसाइट पर जाकर। लाइव डेमो के निम्नलिखित लाभ हैं" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API डाउनलोड करने की आवश्यकता नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" कोई कोड लिखने की जरूरत नहीं है।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" बस अपनी DAE फ़ाइल अपलोड करें, यह तुरंत USDZ में परिवर्तित हो जाएगी।" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" आपको डाउनलोड लिंक मिल जाएगा।" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D सीन मैनिपुलेशन लाइब्रेरी" %}}

 Aspose.3D एक CAD और गेमवेयर API है जो 3D फाइलों को लोड, संशोधित और परिवर्तित करता है। API एक स्टैंडअलोन है और इसके लिए किसी भी 3D मॉडलिंग या रेंडरिंग सॉफ़्टवेयर की आवश्यकता नहीं है। USD, Discreet3DS, WavefrontOBJ, STL (ASCII, बाइनरी), Universal3D, FBX (ASCII, बाइनरी), Collada, glTF के लिए कोई आसानी से API का उपयोग कर सकता है। PLY, GLB, DirectX और अधिक प्रारूप। 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}

DAE फ़ाइल एक डिजिटल एसेट एक्सचेंज फ़ाइल स्वरूप है जिसका उपयोग इंटरैक्टिव 3D अनुप्रयोगों के बीच डेटा के आदान-प्रदान के लिए किया जाता है। यह फ़ाइल प्रारूप कोलाडा (सहयोगात्मक डिजाइन गतिविधि) एक्सएमएल स्कीमा पर आधारित है जो ग्राफिक्स सॉफ्टवेयर अनुप्रयोगों के बीच डिजिटल संपत्तियों के आदान-प्रदान के लिए एक खुला मानक एक्सएमएल स्कीमा है। इसे ISO द्वारा सार्वजनिक रूप से उपलब्ध विनिर्देश, ISO/pAS 17506 के रूप में अपनाया गया है। DAE फाइलें Adobe Photoshop, AutoDesk Maya, AutoDesk AutoCAD, और API जैसे Aspose.CAD जैसे अनुप्रयोगों में खोली जा सकती हैं।

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="USDZ" readMoreLink="https://docs.fileformat.com/3d/usdz/" >}}

.usdz वाली एक फ़ाइल USD (सार्वभौमिक दृश्य विवरण) फ़ाइल स्वरूप के लिए एक असम्पीडित और अनएन्क्रिप्टेड ZIP संग्रह है जिसमें संग्रह के भीतर एम्बेडेड अन्य प्रारूपों (जैसे बनावट, और एनिमेशन) की फ़ाइलों के लिए और प्रॉक्सी शामिल हैं और उन्हें चलाते हैं सीधे USD रन-टाइम के साथ बिना किसी अनपैकिंग की आवश्यकता के। USDZ फाइलें वे पैकेज हैं जिनका डिजाइन एक पैकेज के नए एआर-लेवल एब्स्ट्रैक्शन पर आधारित है। Usdz IANA के साथ पंजीकृत था और इसमें मॉडल का मीडिया प्रकार का नाम और vnd.usd+zip का उप-प्रकार का नाम है और इसका विवरण IANA पंजीकरण पृष्ठ पर पाया जा सकता है।


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="आप DAE को कई अन्य फ़ाइल स्वरूपों में भी परिवर्तित कर सकते हैं जिनमें कुछ नीचे सूचीबद्ध हैं।" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-gltf/" name="DAE से GLTF" description="जीएल ट्रांसमिशन प्रारूप फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-glb/" name="DAE से GLB" description="बाइनरी जीएल ट्रांसमिशन प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-pdf/" name="DAE से PDF" description="वहनीय दस्तावेज़ स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-fbx/" name="DAE से FBX" description="ऑटोडेस्क FBX इंटरचेंज फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-stl/" name="DAE से STL" description="स्टीरियोलिथोग्राफी फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-obj/" name="DAE से OBJ" description="Wavefront 3D ऑब्जेक्ट फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-3ds/" name="DAE से 3DS" description="3D स्टूडियो दृश्य" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-u3d/" name="DAE से U3D" description="Universal 3D फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-ply/" name="DAE से PLY" description="बहुभुज फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-drc/" name="DAE से DRC" description="Google Draco फ़ाइल स्वरूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-rvm/" name="DAE से RVM" description="अवेवा RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-jt/" name="DAE से JT" description="JT खोलें CAD फ़ाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-amf/" name="DAE से AMF" description="एडिटिव मैन्युफैक्चरिंग फाइल" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-html/" name="DAE से HTML" description="हाइपर टेक्स्ट मार्कअप लैंग्वेज" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-usd/" name="DAE से USD" description="यूनिवर्सल सीन विवरण प्रारूप" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-usdz/" name="DAE से USDZ" description="यूनिवर्सल सीन विवरण ज़िप्ड प्रारूप" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}