﻿---
title:  تحويل SXC إلى JPG باستخدام NodeJS
description:  استخدام Aspose.Cells Cloud SDK لـ NodeJS لتحويل ملف بتنسيق SXC إلى ملف بتنسيق JPG.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تحويل SXC إلى JPG" h2="مكتبة NodeJS لتحويل SXC إلى JPG" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع NodeJS. يعد هذا حلاً احترافيًا لتحويل SXC إلى JPG وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام NodeJS." urlsection="conversion/sxc-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل SXC إلى JPG باستخدام Cells Cloud SDK لـ NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من SXC إلى JPG مهمة معقدة. يتعامل NodeJS SDK الخاص بنا مع جميع تحويلات تنسيق SXC إلى JPG مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات SXC المصدر. توفر مكتبة NodeJS الخاصة بنا حلاً احترافيًا لتحويل ملفات SXC إلى JPG عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري NodeJS بوظائف قوية ويضمن إخراج JPG عالي الجودة.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على رمز NodeJS لتحويل SXC إلى JPG باستخدام Cells Cloud SDK" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.sxc"),
        format: "jpg",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لـ Node لتحويل ملفات Excel إلى تنسيقات أخرى من SXC إلى JPG" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>العقدة v6.17.1 أو الأحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
