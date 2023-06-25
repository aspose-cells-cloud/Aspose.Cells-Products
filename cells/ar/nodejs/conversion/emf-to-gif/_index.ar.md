---
title: EMF إلى GIF تحويل API لـ NodeJS
description:  استخدام Aspose.Cells Cloud SDK لـ NodeJS لتحويل ملف تنسيق EMF إلى ملف بتنسيق GIF.
url: /ar/nodejs/conversion/emf-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API لتحويل EMF إلى GIF" h2="مكتبة NodeJS لتحويل EMF إلى GIF" p="استخدم Cells Conversion REST API لإنشاء مسارات عمل جدول البيانات المخصصة في NodeJS. هذا حل احترافي لتحويل EMF إلى GIF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام NodeJS." urlsection="conversion/emf-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تحويل ملف EMF إلى GIF في NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من EMF إلى GIF مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق EMF إلى GIF بواسطة NodeJS SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات EMF المصدر. مكتبة NodeJS الخاصة بنا هي حل احترافي لتحويل EMF إلى ملفات GIF عبر الإنترنت. يمنح Cloud SDK مطوري NodeJS وظائف قوية وإخراج GIF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في NodeJS باستخدام REST API لتحويل EMF إلى تنسيق GIF" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.emf"),
        format: "gif",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Node API لتحويل EMF إلى GIF" >}}
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
