﻿---
title: إضافة علامة مائية عمياء إلى تنسيقات ملفات X عبر .NET 
weight: 830
url: /ar/net/watermark/x/ 
description: C# كود المصدر لتحميل وتقديم وإضافة علامة مائية عمياء إلى مستندات X على .NET Framework ، .NET Core ، Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="إضافة علامة مائية عمياء إلى X عبر C#" h2="قم بإنشاء تطبيقات .NET الخاصة بك لملفات العلامة المائية X باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="X" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="X" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية العلامة المائية إلى X File باستخدام C#" %}}

 من أجل العلامة المائية X الملف ، سوف نستخدم
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API وهي غنية بالميزات وقوية وسهلة الاستخدام API لمنصة C# لاستخدامها مع إضافة أي علامة مائية. فتح
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 مدير الحزمة ، البحث عن
 **Aspose.3D** 
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من وحدة التحكم في مدير الحزمة.

{{% blocks/products/pf/agp/code-block title="حزمة مدير وحدة التحكم القيادة" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات لإضافة علامة مائية عمياء إلى X عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D يجعل من السهل على المطورين إضافة علامة مائية عمياء إلى ملف X مع بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

- تحميل ملف X عبر مُنشئ فئة المشهد- احصل على فئة الشبكة من Aspose.3D- إضافة علامة مائية وكلمة مرور باستخدام Aspose.3D طريقة EncodeWatermark- استدعاء المشهد. حفظ الطريقة مع الكائن
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET مدعوم على جميع أنظمة التشغيل الرئيسية. فقط تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework ، .NET Core ، Mono- بيئة تطوير مثل Microsoft Visual Studio- Aspose.3D for .NET المشار إليها في مشروعك
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# رمز لإضافة علامة مائية عمياء إلى X" offSpacer="" %}}

```cs

//الملف المصدر الذي يحتاج إلى علامة مائية وملف الإخراج بعد الحفظ
string file = "template.x";
string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

// خلق مثيل من المشهد
Scene scene = new Scene(file);

//إضافة علامة مائية وكلمة مرور إلى الملفات
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

//احفظ الملف بالتنسيق الذي تريده
scene.Save(output, FileFormat.FBX7400ASCII);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حوالي Aspose.3D for .NET API" %}}

 Aspose.3D هو CAD و Gameweware API لتحميل وتعديل وتحويل 3D من الملفات. API مستقل ولا يتطلب أي برنامج نمذجة أو عرض 3D. يمكن للمرء بسهولة استخدام API لـ Discreet3DS ، WavefrontOBJ ، STL (ASCII ، ثنائي) ، Universal3D ، FBX (ASCII ، ثنائي) ، Collada ، glTF ، PLY ، GLB ، DirectX والمزيد من التنسيقات. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="تطبيق مجاني لإضافة علامة مائية عمياء إلى X" sectionDescription="تحقق من العروض التوضيحية الحية لدينا [العلامة المائية X](https://products.aspose.app/3d/watermark/x) مع الفوائد التالية." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتحميل أو إعداد أي شيء" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أو تجميع التعليمات البرمجية" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" مجرد تحميل ملف X واضغط على زر \"العلامة المائية\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" قم بتنزيل ملف X من الرابط ، إذا لزم الأمر" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="X" readMoreLink="https://docs.fileformat.com/3d/x/" >}}
X هو ملف صورة من طراز DirectX تستخدمه تقنية DirectX وهو لـ 3D عرض الرسومات في الألعاب. يحدد تنسيق الملف 3D هياكل الكائنات للشبكات والقوام والرسوم المتحركة والكائنات.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="التطبيقات المدعومة الأخرى لإضافة العلامة المائية العمياء إلى التنسيقات" subTitle="باستخدام C# ، يمكن للمرء أيضًا إضافة علامة مائية عمياء إلى العديد من تنسيقات الملفات الأخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3mf/" name="3MF" description="3D تنسيق التصنيع" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/amf/" name="AMF" description="صيغة التصنيع المضافة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/ase/" name="ASE" description="ملف الرسوم المتحركة 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dae/" name="DAE" description="تبادل الأصول الرقمية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dxf/" name="DXF" description="رسم تنسيق التبادل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/fbx/" name="FBX" description="3D الشكل" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/glb/" name="GLB" description="3D ملف التمثيل الثنائي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/gltf/" name="GLTF" description="تنسيق إرسال GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/jt/" name="JT" description="كوكب المشتري ملف" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/obj/" name="OBJ" description="3D تنسيق الملف" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/ply/" name="PLY" description="تنسيق ملف المضلع" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/rvm/" name="RVM" description="نموذج تصميم مصنع AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/stl/" name="STL" description="قابلة للتبديل 3D هندسة السطح" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/vrml/" name="VRML" description="لغة نمذجة الواقع الافتراضي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3ds/" name="3DS" description="3D تنسيق ملف شبكة الاستوديو" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usd/" name="USD" description="وصف المشهد العالمي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usdz/" name="USDZ" description="وصف المشهد العالمي أرشيف الرمز البريدي" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}