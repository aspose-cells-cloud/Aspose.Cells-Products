﻿---
title:  احفظ HTML كـ PDF باستخدام C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لحفظ ملف بتنسيق HTML كملف بتنسيق PDF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="احفظ HTML كـ PDF" h2="مكتبة C# لحفظ HTML باسم PDF" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Net. يعد هذا حلاً احترافيًا لحفظ HTML كـ PDF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام C#." urlsection="saveas/html-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف HTML كـ PDF في C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من HTML إلى PDF مهمة معقدة. يتم تنفيذ جميع انتقالات التنسيق من HTML إلى PDF بواسطة C# SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات HTML. تعد مكتبتنا C# حلاً احترافيًا لحفظ HTML كملفات PDF عبر الإنترنت. يمنح Cloud SDK هذا مطوري C# وظائف قوية وإخراج PDF مثاليًا.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# مثال على حفظ HTML كـ PDF باستخدام REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.html";
    string newfilename = "Book1SaveAs.pdf";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK for Net لحفظ Excel ملف بتنسيقات أخرى HTML كـ PDF" >}}
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
