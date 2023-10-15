---
title:  احفظ ODS كـ TSV باستخدام NodeJS
description:  استخدام Aspose.Cells Cloud SDK لـ NodeJS لحفظ ملف بتنسيق ODS كملف بتنسيق TSV.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="حفظ المواد المستنفدة للأوزون كـ TSV" h2="مكتبة NodeJS لحفظ المواد المستنفدة للأوزون بصيغة TSV" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في NodeJS. يعد هذا حلاً احترافيًا لحفظ المواد المستنفدة للأوزون بتنسيق TSV وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام NodeJS." urlsection="saveas/ods-to-tsv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف ODS بتنسيق TSV في NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من ODS بتنسيق TSV مهمة معقدة. يتم تنفيذ جميع عمليات النقل من تنسيق ODS إلى TSV بواسطة NodeJS SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات ODS المصدر. تعد مكتبة NodeJS الخاصة بنا حلاً احترافيًا لحفظ المواد المستنفدة للأوزون كملفات TSV عبر الإنترنت. يوفر Cloud SDK لمطوري NodeJS وظائف قوية ومخرجات TSV مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على رمز NodeJS لحفظ المواد المستنفدة للأوزون كـ TSV باستخدام REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.ods",
      folder: "CellsTests",
      newfilename: "Book1Saveas.tsv",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK للعقدة لحفظ ملفات Excel بتنسيقات أخرى ODS مثل TSV" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `PostWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>العقدة v6.17.1 أو الأحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
