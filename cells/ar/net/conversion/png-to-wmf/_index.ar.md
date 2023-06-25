---
title:  PNG إلى WMF تحويل API ل C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لتحويل ملف تنسيق PNG إلى ملف بتنسيق WMF.
url: /ar/net/conversion/png-to-wmf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API لتحويل PNG إلى WMF" h2="مكتبة C# لتحويل PNG إلى WMF" p="استخدم Cells Conversion REST API لإنشاء مسارات عمل جدول بيانات مخصصة في Net. هذا حل احترافي لتحويل PNG إلى WMF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام C#." urlsection="conversion/png-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف PNG إلى WMF في C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من PNG إلى WMF مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق PNG إلى WMF بواسطة C# SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول البيانات PNG المصدر. تعد مكتبتنا C# حلاً احترافيًا لتحويل PNG إلى ملفات WMF عبر الإنترنت. يوفر Cloud SDK للمطورين C# وظائف قوية وإخراج WMF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في C# باستخدام REST API لتحويل PNG إلى تنسيق WMF" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.png";
    string format = "wmf";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.wmf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام C# API لتحويل PNG إلى WMF" >}}
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
