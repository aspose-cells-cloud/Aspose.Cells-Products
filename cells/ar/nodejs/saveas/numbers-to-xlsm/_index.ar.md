﻿---
title:  حفظ الأرقام كـ XLSM API لـ NodeJS
description:  Cloud APIs & SDKs لـ Microsoft Excel & OpenOffice Calc. تحويل جدول البيانات إلى ملف تنسيق آخر.
url: /ar/nodejs/saveas/numbers-to-xlsm/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API لحفظ الأرقام كـ XLSM" h2="مكتبة NodeJS لحفظ الأرقام كـ XLSM" p="استخدم Cells SaveAs REST API لتكوين مسارات عمل جدول بيانات مهيأة في NodeJS. هذا حل احترافي لحفظ NUMBERS بتنسيق XLSM وتنسيقات مستندات أخرى عبر الإنترنت باستخدام NodeJS." urlsection="saveas/numbers-to-xlsm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف NUMBERS بتنسيق XLSM في NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من NUMBERS كـ XLSM مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق NUMBERS إلى XLSM بواسطة NodeJS SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات NUMBERS المصدر. مكتبة NodeJS الخاصة بنا هي حل احترافي لحفظ الأرقام كملفات XLSM عبر الإنترنت. يمنح Cloud SDK مطوري NodeJS وظائف قوية وإخراج XLSM مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في NodeJS باستخدام REST API لحفظ الأرقام بتنسيق XLSM" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.numbers",
      folder: "CellsTests",
      newfilename: "Book1Saveas.xlsm",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Node API لحفظ الأرقام كـ XLSM" >}}
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