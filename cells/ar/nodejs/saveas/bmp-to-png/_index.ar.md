---
title:  احفظ BMP كـ PNG API من أجل NodeJS
description:  استخدام Aspose.Cells Cloud SDK لـ NodeJS لحفظ ملف بتنسيق BMP كملف بتنسيق PNG.
url: /ar/nodejs/saveas/bmp-to-png/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API لحفظ BMP كـ PNG" h2="مكتبة NodeJS لحفظ BMP كـ PNG" p="استخدم Cells SaveAs REST API لتكوين مسارات عمل جدول بيانات مهيأة في NodeJS. هذا حل احترافي لحفظ BMP كـ PNG وتنسيقات مستندات أخرى عبر الإنترنت باستخدام NodeJS." urlsection="saveas/bmp-to-png/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف BMP بالشكل PNG في NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من BMP كـ PNG مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق BMP إلى PNG بواسطة NodeJS SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول البيانات BMP المصدر. مكتبة NodeJS الخاصة بنا هي حل احترافي لحفظ BMP كملفات PNG عبر الإنترنت. يمنح Cloud SDK مطوري NodeJS وظائف قوية وإخراج PNG مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في NodeJS باستخدام REST API لحفظ BMP بتنسيق PNG" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.bmp",
      folder: "CellsTests",
      newfilename: "Book1Saveas.png",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Node API لحفظ BMP كـ PNG" >}}
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
