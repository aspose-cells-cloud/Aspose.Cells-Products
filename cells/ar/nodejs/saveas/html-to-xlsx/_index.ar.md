---
title:  وفر HTML كـ XLSX API من أجل NodeJS
description:  استخدام Aspose.Cells Cloud SDK لـ NodeJS لحفظ ملف بتنسيق HTML كملف بتنسيق XLSX.
url: /ar/nodejs/saveas/html-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API لحفظ HTML كـ XLSX" h2="مكتبة NodeJS لحفظ HTML كـ XLSX" p="استخدم Cells SaveAs REST API لتكوين مسارات عمل جدول بيانات مهيأة في NodeJS. هذا حل احترافي لحفظ HTML بتنسيق XLSX وتنسيقات مستندات أخرى عبر الإنترنت باستخدام NodeJS." urlsection="saveas/html-to-xlsx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف HTML كـ XLSX في NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من HTML كـ XLSX مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق HTML إلى XLSX بواسطة NodeJS SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول البيانات HTML المصدر. مكتبة NodeJS الخاصة بنا هي حل احترافي لحفظ HTML كملفات XLSX عبر الإنترنت. يمنح Cloud SDK مطوري NodeJS وظائف قوية وإخراج XLSX مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في NodeJS باستخدام REST API لحفظ HTML بتنسيق XLSX" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.html",
      folder: "CellsTests",
      newfilename: "Book1Saveas.xlsx",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Node API لحفظ HTML كـ XLSX" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة cellSaveAsPostDocumentSaveAs للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>العقدة v6.17.1 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
