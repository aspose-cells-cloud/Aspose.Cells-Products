---
title:  تحويل XLTM إلى FODS باستخدام C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لتحويل ملف تنسيق XLTM إلى ملف تنسيق FODS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تحويل XLTM إلى FODS" h2="C# مكتبة لتحويل XLTM إلى FODS" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Net. يعد هذا حلاً احترافيًا لتحويل XLTM إلى FODS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام C#." urlsection="conversion/xltm-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تحويل XLTM إلى FODS باستخدام Cells Cloud SDK لـ C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من XLTM إلى FODS مهمة معقدة. يتعامل SDK C# الخاص بنا مع جميع تحويلات تنسيق XLTM إلى FODS مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLTM المصدر. توفر مكتبتنا C# حلاً احترافيًا لتحويل ملفات XLTM إلى ملفات FODS عبر الإنترنت. يعمل Cloud SDK هذا على تمكين مطوري C# من الحصول على وظائف قوية ويضمن إخراج FODS عالي الجودة.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# مثال على الكود لتحويل XLTM إلى FODS باستخدام Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xltm";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK for Net لتحويل ملفات Excel إلى تنسيقات أخرى XLTM إلى FODS" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `PutConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>NET Framework 4.5.2 أو أحدث</li>
<li>نت ستاندرد 2.0 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
