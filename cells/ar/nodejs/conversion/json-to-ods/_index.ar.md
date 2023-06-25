---
title: JSON إلى ODS - تحويل API لـ NodeJS
description:  استخدام Aspose.Cells Cloud SDK لـ NodeJS لتحويل ملف تنسيق JSON إلى ملف بتنسيق ODS.
url: /ar/nodejs/conversion/json-to-ods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API لتحويل JSON إلى ODS" h2="مكتبة NodeJS لتحويل JSON إلى ODS" p="استخدم Cells Conversion REST API لإنشاء مسارات عمل جدول البيانات المخصصة في NodeJS. هذا حل احترافي لتحويل JSON إلى ODS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام NodeJS." urlsection="conversion/json-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تحويل ملف JSON إلى ODS في NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من JSON إلى ODS مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق JSON إلى ODS بواسطة NodeJS SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات JSON المصدر. تعد مكتبة NodeJS الخاصة بنا حلاً احترافيًا لتحويل ملفات JSON إلى ملفات ODS عبر الإنترنت. يمنح Cloud SDK مطوري NodeJS وظائف قوية وإخراج ODS مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في NodeJS باستخدام REST API لتحويل JSON إلى تنسيق ODS" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.json"),
        format: "ods",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Node API لتحويل JSON إلى ODS" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة cellWorkbookPutConvertWorkbook للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>العقدة v6.17.1 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
