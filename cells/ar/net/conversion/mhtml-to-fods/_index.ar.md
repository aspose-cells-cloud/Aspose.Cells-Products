---
title:  MHTML إلى FODS - تحويل API إلى C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لتحويل ملف تنسيق MHTML إلى ملف بتنسيق FODS.
url: /ar/net/conversion/mhtml-to-fods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API لتحويل MHTML إلى FODS" h2="مكتبة C# لتحويل MHTML إلى FODS" p="استخدم Cells Conversion REST API لإنشاء مسارات عمل جدول بيانات مخصصة في Net. هذا حل احترافي لتحويل MHTML إلى FODS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام C#." urlsection="conversion/mhtml-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف MHTML إلى FODS في C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من MHTML إلى FODS مهمة معقدة. يتم إجراء جميع انتقالات تنسيق MHTML إلى FODS بواسطة C# SDK مع الحفاظ على المحتوى البنيوي والمنطقي الرئيسي لجدول بيانات MHTML المصدر. تعد مكتبتنا C# حلاً احترافيًا لتحويل ملفات MHTML إلى ملفات FODS عبر الإنترنت. يوفر Cloud SDK للمطورين C# وظائف قوية وإخراج FODS مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في C# باستخدام REST API لتحويل MHTML إلى تنسيق FODS" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.mhtml";
    string format = "fods";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.fods";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام C# API لتحويل MHTML إلى FODS" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة CellsWorkbookPutConvertWorkbook للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>NET Framework 4.5.2 أو أحدث</li>
<li>Net Standard 2.0 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
