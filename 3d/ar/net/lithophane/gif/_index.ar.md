﻿---
title: قم بإنشاء Lithophane من تنسيقات ملف GIF عبر .NET 
weight: 830
url: /ar/net/lithophane/gif/ 
description: C# شفرة المصدر لتحميل وعرض وإنشاء مستندات الليثوفاني الخاصة بك إلى GIF على .NET Framework ، .NET Core ، Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="قم بإنشاء Lithophane إلى GIF عبر C#" h2="أنشئ تطبيقاتك البالغ عددها .NET لإنشاء ملفات الليثوفاني إلى ملفات GIF باستخدام واجهات برمجة التطبيقات من جانب الخادم." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GIF" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="GIF" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GIF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية إنشاء ملف Lithophane إلى GIF باستخدام C#" %}}

 من أجل إنشاء ملف lithophane إلى GIF ، سنستخدمه
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API وهو نظام غني بالميزات وقوي وسهل الاستخدام API لـ C# نظام أساسي لاستخدامه في إنشاء مادة الليثوفان الخاصة بك. افتح
 [نوجيت](https://www.nuget.org/packages/aspose.3d) 
 مدير الحزم ، ابحث عن
 ** Aspose.3D ** 
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{% blocks/products/pf/agp/code-block title="أمر وحدة تحكم مدير الحزم" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات إنشاء Lithophane الخاص بك إلى GIF عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

 يسهل Aspose.3D على المطورين إنشاء مادة الليثوفاني الخاصة بك إلى ملف GIF باستخدام بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

- قم بإنشاء بعض المعلمات الجديدة وإنشاء كائن شبكة- إجراء عمليات حسابية على كائنات الشبكة- يقوم ملف GIF بتحميل مشهد ثلاثي الأبعاد من خلال فئة Mesh- استدعاء طريقة Scene.Save مع الكائن
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET مدعوم في جميع أنظمة التشغيل الرئيسية. فقط تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework ، .NET Core ، Mono- بيئة التطوير مثل Microsoft Visual Studio- تمت الإشارة إلى Aspose.3D for .NET في مشروعك
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# لإنشاء ليثوفاني الخاص بك إلى GIF" offSpacer="" %}}

```cs

//الصورة الأصلية المراد رفعها وإخراج الملف ثلاثي الأبعاد بعد الحفظ
    string file = "template.gif";
    string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

//قم بإنشاء بعض المعلمات الجديدة
    var td= TextureData.FromFile(file);
    const float nozzleSize = 0.9f;//0.2 مم
    const float layerHeight = 0.2f;
    var grayscale = ToGrayscale(td);
    const float width = 120.0f;//عرض القماش 200.0 مم
    float height = width / td.Width * td.Height;
    float thickness = 10.0f;//سمك 10 مم
    float layers = thickness / layerHeight;
    int widthSegs = (int)Math.Floor(width / nozzleSize);
    int heightSegs = (int)Math.Floor(height / nozzleSize);

//إجراء عمليات حسابية على كائنات الشبكة
    var mesh = new Mesh();
    for (int y = 0; y < heightSegs; y++)
    {
        float dy = (float)y / heightSegs;
        for (int x = 0; x < widthSegs; x++)
        {
            float dx = (float)x / widthSegs;
            float gray = Sample(grayscale, td.Width, td.Height, dx, dy);
            float v = (1 - gray) * thickness;
            mesh.ControlPoints.Add(new Vector4(dx * width, dy * height, v));
        }
    }


    for (int y = 0; y < heightSegs - 1; y++)
    {
        int row = (y * heightSegs);
        int ptr = row;
        for (int x = 0; x < widthSegs - 1; x++)
        {
            mesh.CreatePolygon(ptr, ptr + widthSegs, ptr + 1);
            mesh.CreatePolygon(ptr + 1, ptr + widthSegs, ptr + widthSegs + 1);
            ptr++;
        }
    }

//إنشاء مشهد ثلاثي الأبعاد وحفظ الكائنات
    var scene = new Scene(mesh);
    scene.Save(output, FileFormat.FBX7400ASCII);

//طريقة العينة للاتصال
    static float Sample(float[,] data, int w, int h, float x, float y)
    {
        return data[(int)(x * w), (int)(y * h)];
    }

//طريقة ToGrayscale للاتصال
    static float[,] ToGrayscale(TextureData td)
    {
        var ret = new float[td.Width, td.Height];
        var stride = td.Stride;
        var data = td.Data;
        var bytesPerPixel = td.BytesPerPixel;
        for (int y = 0; y < td.Height; y++)
        {
            int ptr = y * stride;
            for (int x = 0; x < td.Width; x++)
            {
                var v = (data[ptr] * 0.21f + data[ptr + 1] * 0.72f + data[ptr + 2] * 0.07f) / 255.0f;
                ret[x, y] = v;
                ptr += bytesPerPixel;
            }
        }
        return ret;
    }

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.3D for .NET API" %}}

 Aspose.3D هو برنامج ألعاب CAD وألعاب API لتحميل وتعديل وتحويل ملفات 3D. API هو برنامج قائم بذاته ولا يتطلب أي 3D برامج عرض أو نماذج. يمكن للمرء بسهولة استخدام API لـ Discreet3DS ، WavefrontOBJ ، STL (ASCII ، ثنائي) ، Universal3D ، FBX (ASCII ، ثنائي) ، Collada ، glTF ، PLY ، GLB و DirectX والمزيد من التنسيقات. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="تطبيق مجاني لإنشاء Lithophane الخاص بك إلى GIF" sectionDescription="تحقق من العروض الحية لدينا ل [الليثوفان GIF](https://products.aspose.app/3d/lithophane/gif) مع الفوائد التالية." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل أو إعداد أي شيء" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أو ترجمة التعليمات البرمجية" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" فقط قم بتحميل ملف GIF واضغط على زر \"lithophane\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" قم بتنزيل ملف GIF من الرابط ، إذا لزم الأمر" >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تطبيق مدعوم آخر لإنشاء تنسيقات Lithophane" subTitle="باستخدام C# ، يمكن للمرء أيضًا إنشاء الليثوفاني الخاص بك إلى العديد من تنسيقات الملفات الأخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/jpeg/" name="JPEG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/png/" name="بي إن جي" description="رسومات الشبكة المحمولة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/tga/" name="TGA" description="محول Truevision Advanced Raster" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/bmp/" name="BMP" description="نقطية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/jpg/" name="JPG" description="مجموعة خبراء التصوير المشتركة" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/tiff/" name="شجار" description="الموسومة تنسيق ملف الصورة" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}