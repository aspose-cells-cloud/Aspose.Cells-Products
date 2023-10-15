---
title:  تحويل XLSB إلى PNG باستخدام C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لتحويل ملف بتنسيق XLSB إلى ملف بتنسيق PNG.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تحويل XLSB إلى PNG" h2="مكتبة C# لتحويل XLSB إلى PNG" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Net. يعد هذا حلاً احترافيًا لتحويل XLSB إلى PNG وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام C#." urlsection="conversion/xlsb-to-png/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تحويل XLSB إلى PNG باستخدام Cells Cloud SDK لـ C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من XLSB إلى PNG مهمة معقدة. يتعامل SDK C# الخاص بنا مع جميع تحويلات تنسيق XLSB إلى PNG مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLSB المصدر. توفر مكتبتنا C# حلاً احترافيًا لتحويل ملفات XLSB إلى PNG عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري C# بوظائف قوية ويضمن إخراج PNG عالي الجودة.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# مثال على الكود لتحويل XLSB إلى PNG باستخدام Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsb";
    string format = "png";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.png";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK for Net لتحويل ملفات Excel إلى تنسيقات أخرى XLSB إلى PNG" >}}
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
