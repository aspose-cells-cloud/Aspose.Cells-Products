---
title:  تحويل XLS إلى XLTX باستخدام C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لتحويل ملف بتنسيق XLS إلى ملف بتنسيق XLTX.
kwords: Excel, Convert XLS to XLTX, REST, C#
howto: How to convert XLS to XLTX using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل XLS إلى XLTX" h2="مكتبة C# لتحويل XLS إلى XLTX" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Net. يعد هذا حلاً احترافيًا لتحويل XLS إلى XLTX وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام C#." urlsection="conversion/xls-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل XLS إلى XLTX باستخدام Cells Cloud SDK لـ C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من XLS إلى XLTX مهمة معقدة. يتعامل SDK C# الخاص بنا مع جميع تحويلات تنسيق XLS إلى XLTX مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLS المصدر. توفر مكتبتنا C# حلاً احترافيًا لتحويل ملفات XLS إلى XLTX عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري C# من الحصول على وظائف قوية ويضمن إخراج XLTX عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# مثال على الكود لتحويل XLS إلى XLTX باستخدام Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xls";
    string format = "xltx";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xltx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية تحويل XLS إلى XLTX باستخدام مكتبة Cells Cloud Net." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة C# وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في C#</li>
<li>استخدم طريقة `PutConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>NET Framework 4.5.2 أو أحدث</li>
<li>نت ستاندرد 2.0 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
