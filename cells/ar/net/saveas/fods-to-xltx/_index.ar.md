---
title:  احفظ FODS كـ XLTX باستخدام C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لحفظ ملف تنسيق FODS كملف تنسيق XLTX.
kwords: Excel, Save FODS as XLTX, REST, C#
howto: How to save FODS as XLTX using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ FODS بصيغة XLTX" h2="C# مكتبة لحفظ FODS بصيغة XLTX" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Net. يعد هذا حلاً احترافيًا لحفظ FODS بتنسيق XLTX وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام C#." urlsection="saveas/fods-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف FODS بتنسيق XLTX في C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من FODS بتنسيق XLTX مهمة معقدة. يتم تنفيذ جميع التحولات من تنسيق FODS إلى XLTX بواسطة C# SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات FODS. تعد مكتبتنا C# حلاً احترافيًا لحفظ FODS كملفات XLTX عبر الإنترنت. يوفر Cloud SDK هذا لمطوري C# وظائف قوية ومخرجات XLTX مثالية.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# مثال على كود حفظ FODS بصيغة XLTX باستخدام REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.fods";
    string newfilename = "Book1SaveAs.xltx";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="تعرف على كيفية حفظ FODS بتنسيق XLTX باستخدام مكتبة Cloud Net Cells." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة C# وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في C#</li>
<li>استخدم طريقة `PostWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>NET Framework 4.5.2 أو أحدث</li>
<li>نت ستاندرد 2.0 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
