---
title:  احفظ PNG بصيغة JPG باستخدام C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لحفظ ملف بتنسيق PNG كملف بتنسيق JPG.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="احفظ PNG بصيغة JPG" h2="مكتبة C# لحفظ PNG بصيغة JPG" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Net. يعد هذا حلاً احترافيًا لحفظ PNG بتنسيق JPG وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام C#." urlsection="saveas/png-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف PNG بتنسيق JPG في C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من PNG بتنسيق JPG مهمة معقدة. يتم تنفيذ جميع التحولات من تنسيق PNG إلى JPG بواسطة C# SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات PNG. تعد مكتبتنا C# حلاً احترافيًا لحفظ PNG كملفات JPG عبر الإنترنت. يوفر Cloud SDK هذا لمطوري C# وظائف قوية ومخرجات JPG مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# مثال على الكود لحفظ PNG بصيغة JPG باستخدام REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.png";
    string newfilename = "Book1SaveAs.jpg";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK for Net لحفظ Excel ملف بتنسيقات أخرى PNG بصيغة JPG" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `PostWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
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
