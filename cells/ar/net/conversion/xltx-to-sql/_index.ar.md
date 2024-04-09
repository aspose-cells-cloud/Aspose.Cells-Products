---
title:  تحويل XLTX إلى SQL باستخدام C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لتحويل ملف تنسيق XLTX إلى ملف تنسيق SQL.
kwords: Excel, Convert XLTX to SQL, REST, C#
howto: How to convert XLTX to SQL using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل XLTX إلى SQL" h2="مكتبة C# لتحويل XLTX إلى SQL" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Net. يعد هذا حلاً احترافيًا لتحويل XLTX إلى SQL وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام C#." urlsection="conversion/xltx-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل XLTX إلى SQL باستخدام Cells Cloud SDK لـ C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من XLTX إلى SQL مهمة معقدة. يتعامل SDK C# الخاص بنا مع جميع تحويلات تنسيق XLTX إلى SQL مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLTX المصدر. توفر مكتبتنا C# حلاً احترافيًا لتحويل ملفات XLTX إلى ملفات SQL عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري C# من الحصول على وظائف قوية ويضمن إخراج SQL عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# مثال على الكود لتحويل XLTX إلى SQL باستخدام Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xltx";
    string format = "sql";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.sql";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية تحويل XLTX إلى SQL باستخدام مكتبة Cloud Net Cells." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة C# وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في C#</li>
<li>استخدم طريقة `PutConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>NET Framework 4.5.2 أو أحدث</li>
<li>نت ستاندرد 2.0 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
