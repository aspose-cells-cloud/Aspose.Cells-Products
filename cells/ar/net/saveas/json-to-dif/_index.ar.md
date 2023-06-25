---
title:  احفظ JSON باسم DIF API مقابل C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لحفظ ملف بتنسيق JSON كملف بتنسيق DIF.
url: /ar/net/saveas/json-to-dif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API لحفظ JSON كـ DIF" h2="مكتبة C# لحفظ JSON كـ DIF" p="استخدم Cells SaveAs REST API لإنشاء مسارات عمل جدول بيانات مخصصة في Net. هذا حل احترافي لحفظ JSON بتنسيق DIF وتنسيقات مستندات أخرى عبر الإنترنت باستخدام C#." urlsection="saveas/json-to-dif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف JSON كملف DIF في C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من JSON كـ DIF مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق JSON إلى DIF بواسطة C# SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات JSON المصدر. تعد مكتبتنا C# حلاً احترافيًا لحفظ JSON كملفات DIF عبر الإنترنت. يوفر Cloud SDK للمطورين C# وظائف قوية وإخراج DIF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في C# باستخدام REST API لحفظ JSON بتنسيق DIF" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.json";
    string newfilename = "Book1SaveAs.dif";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام C# API لحفظ JSON كـ DIF" >}}
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
