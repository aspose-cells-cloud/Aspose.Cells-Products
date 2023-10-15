---
title:  احفظ JPG بتنسيق FODS باستخدام NodeJS
description:  استخدام Aspose.Cells Cloud SDK لـ NodeJS لحفظ ملف بتنسيق JPG كملف بتنسيق FODS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="احفظ JPG بصيغة FODS" h2="مكتبة NodeJS لحفظ JPG بصيغة FODS" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في NodeJS. يعد هذا حلاً احترافيًا لحفظ JPG بتنسيق FODS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام NodeJS." urlsection="saveas/jpg-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="احفظ ملف JPG بتنسيق FODS في NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من JPG بتنسيق FODS مهمة معقدة. يتم تنفيذ جميع عمليات النقل من تنسيق JPG إلى FODS بواسطة NodeJS SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات JPG المصدر. تعد مكتبة NodeJS الخاصة بنا حلاً احترافيًا لحفظ JPG كملفات FODS عبر الإنترنت. يوفر Cloud SDK لمطوري NodeJS وظائف قوية ومخرجات FODS مثالية.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على رمز NodeJS لحفظ JPG كـ FODS باستخدام REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.jpg",
      folder: "CellsTests",
      newfilename: "Book1Saveas.fods",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK للعقدة لحفظ ملفات Excel بتنسيقات أخرى JPG مثل FODS" >}}
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
