---
title:  تصدير ورقة عمل إلى DOCX من Excel باستخدام Cells Cloud SDK لـ C#
description:  Aspose.Cells Cloud REST API يدعم تصدير الملفات بتنسيق {0} إلى {1} باستخدام {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="تصدير ورقة العمل إلى DOCX من Excel" h2="مكتبة C# لتصدير ورقة العمل إلى ملف DOCX" p="استخدم تصدير API من Cells Cloud لتصدير سير عمل الكائن الداخلي لملف Excel في Net. يعد هذا حلاً احترافيًا لتصدير ورقة العمل إلى ملف بتنسيق DOCX من جدول البيانات عبر الإنترنت باستخدام C#." urlsection="export/worksheet-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="تصدير كائن ورقة العمل إلى ملف بتنسيق DOCX باستخدام Cells Cloud SDK لـ C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن ورقة العمل إلى ملف DOCX من الملف Excel مهمة معقدة. يتم تنفيذ انتقالات تصدير ورقة العمل إلى تنسيق DOCX بواسطة C# SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات المصدر. تعد مكتبتنا C# حلاً احترافيًا لتصدير كائنات ورقة العمل إلى ملفات بتنسيق DOCX عبر الإنترنت. يوفر Cloud SDK هذا لمطوري C# وظائف قوية ومخرجات DOCX مثالية.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على الكود في C# باستخدام REST API لتصدير ورقة العمل إلى تنسيق DOCX من جدول البيانات" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string format = "docx";
    string objectType ="worksheet";
    LightCellsApi lightCellsApi =
        new LightCellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    IDictionary<string ,Stream> files = new  Dictionary<string ,Stream>();
    files.Add("Book1.xlsx" , File.OpenRead("Book1.xlsx"));
    files.Add("myDocument.xlsx", File.OpenRead("myDocument.xlsx"));
    var filesResult = lightCellsApi.PostExport(files, objectType, format);
    foreach (var file in filesResult.Files)
    {
        string v = file.FileContent;
        string filename = file.Filename;
        byte[] workbookData = System.Convert.FromBase64String(v);
        MemoryStream memoryStream = new MemoryStream(workbookData, 0, workbookData.Length);
        memoryStream.Seek(0, SeekOrigin.Begin);
        using (FileStream fileStream = File.Create( filename))
        {
            fileStream.Position = 0;
            memoryStream.CopyTo(fileStream);
            fileStream.Close();
        }
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK for Net لتصدير الكائنات من ورقة عمل Excel إلى DOCX" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `postExport` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>NET Framework 4.5.2 أو أحدث</li>
<li>نت ستاندرد 2.0 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
