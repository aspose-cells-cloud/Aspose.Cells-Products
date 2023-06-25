---
title:  احفظ JSON باسم WMF API مقابل C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لحفظ ملف بتنسيق JSON كملف بتنسيق WMF.
url: /ar/net/saveas/json-to-wmf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API لحفظ JSON كـ WMF" h2="مكتبة C# لحفظ JSON كـ WMF" p="استخدم Cells SaveAs REST API لإنشاء مسارات عمل جدول بيانات مخصصة في Net. هذا حل احترافي لحفظ JSON بتنسيق WMF وتنسيقات مستندات أخرى عبر الإنترنت باستخدام C#." urlsection="saveas/json-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف JSON كملف WMF في C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من JSON مثل WMF مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق JSON إلى WMF بواسطة C# SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات JSON المصدر. مكتبتنا C# هي حل احترافي لحفظ JSON كملفات WMF عبر الإنترنت. يوفر Cloud SDK للمطورين C# وظائف قوية وإخراج WMF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في C# باستخدام REST API لحفظ JSON بتنسيق WMF" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.json";
    string newfilename = "Book1SaveAs.wmf";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام C# API لحفظ JSON كـ WMF" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة CellsSaveAsPostDocumentSaveAs للحصول على الدفق الناتج</li>
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
