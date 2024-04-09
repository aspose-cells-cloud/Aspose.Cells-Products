---
title:  تصدير الرسم البياني إلى TIFF من Excel باستخدام Cells Cloud SDK لـ NodeJS
description:  Aspose.Cells Cloud REST API يدعم تصدير الملفات بتنسيق {0} إلى {1} باستخدام {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="تصدير الرسم البياني إلى TIFF من Excel" h2="مكتبة NodeJS لتصدير CHART إلى ملف TIFF" p="استخدم تصدير API من Cells Cloud لتصدير سير عمل الكائن الداخلي للملف Excel في NodeJS. يعد هذا حلاً احترافيًا لتصدير CHART إلى ملف بتنسيق TIFF من جدول البيانات عبر الإنترنت باستخدام NodeJS." urlsection="export/chart-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="تصدير كائن CHART إلى ملف بتنسيق TIFF باستخدام Cells Cloud SDK لـ NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن CHART إلى ملف TIFF من ملف Excel مهمة معقدة. يتم تنفيذ انتقالات تنسيق تصدير CHART إلى تنسيق TIFF بواسطة NodeJS SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات CHART المصدر. تعد مكتبة NodeJS الخاصة بنا حلاً احترافيًا لتصدير كائنات CHART إلى ملفات بتنسيق TIFF عبر الإنترنت. يوفر Cloud SDK لمطوري NodeJS وظائف قوية وإخراج TIFF مثاليًا.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال التعليمات البرمجية في NodeJS باستخدام REST API لتصدير CHART إلى تنسيق TIFF من جدول البيانات" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { LightCellsApi, PostExportRequest } = require("asposecellscloud");
    const localPath = "C:/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new LightCellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    const AssemblyTestXlsx = "assemblytest.xlsx";
    var dataAssemblyTestXlsx =fs.createReadStream(localPath  + AssemblyTestXlsx);
    const DataSourceXlsx = "datasource.xlsx";
    var dataDataSourceXlsx =fs.createReadStream(localPath  + DataSourceXlsx);
    var req = new PostExportRequest({
      file:{AssemblyTestXlsx:dataAssemblyTestXlsx ,DataSourceXlsx:dataDataSourceXlsx },
      objectType : "chart",
      format: "tiff",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK للعقدة لتصدير الكائنات من Excel CHART إلى TIFF" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `postExport` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>العقدة v6.17.1 أو الأحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
