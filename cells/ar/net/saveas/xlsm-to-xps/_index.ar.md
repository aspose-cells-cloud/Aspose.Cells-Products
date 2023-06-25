---
title:  احفظ XLSM كـ XPS API لـ C#
description:  استخدام Aspose.Cells Cloud SDK لـ C# لحفظ ملف بتنسيق XLSM كملف بتنسيق XPS.
url: /ar/net/saveas/xlsm-to-xps/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API لحفظ XLSM بالشكل XPS" h2="مكتبة C# لحفظ XLSM كـ XPS" p="استخدم Cells SaveAs REST API لإنشاء مسارات عمل جدول بيانات مخصصة في Net. هذا حل احترافي لحفظ XLSM كـ XPS وتنسيقات مستندات أخرى عبر الإنترنت باستخدام C#." urlsection="saveas/xlsm-to-xps/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف XLSM بالشكل XPS في C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من XLSM كـ XPS مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XLSM إلى XPS بواسطة C# SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات XLSM المصدر. مكتبتنا C# هي حل احترافي لحفظ XLSM كملفات XPS عبر الإنترنت. يوفر Cloud SDK للمطورين C# وظائف قوية وإخراج XPS مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في C# باستخدام REST API لحفظ XLSM بتنسيق XPS" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsm";
    string newfilename = "Book1SaveAs.xps";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام C# API لحفظ XLSM كـ XPS" >}}
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
