---
title:  احفظ FODS بتنسيق XLS باستخدام NodeJS
description:  استخدام Aspose.Cells Cloud SDK لـ NodeJS لحفظ ملف تنسيق FODS كملف تنسيق XLS.
kwords: Excel, Save FODS as XLS, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save FODS as XLS using the Cells Cloud NodeJS library.","description": "How to save FODS as XLS using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/saveas/fods-to-xls/","step": [{ "@type": "HowToStep","name": "How to save FODS as XLS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/fods-to-xls/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save FODS as XLS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/fods-to-xls/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save FODS as XLS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/fods-to-xls/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to save FODS as XLS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/fods-to-xls/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ FODS بصيغة XLS" h2="مكتبة NodeJS لحفظ FODS بصيغة XLS" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في NodeJS. يعد هذا حلاً احترافيًا لحفظ FODS بتنسيق XLS وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام NodeJS." urlsection="saveas/fods-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف FODS بتنسيق XLS في NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من FODS بتنسيق XLS مهمة معقدة. يتم تنفيذ جميع التحولات من تنسيق FODS إلى XLS بواسطة NodeJS SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات FODS المصدر. تعد مكتبة NodeJS الخاصة بنا حلاً احترافيًا لحفظ FODS كملفات XLS عبر الإنترنت. يوفر Cloud SDK لمطوري NodeJS وظائف قوية ومخرجات XLS مثالية.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على كود NodeJS لحفظ FODS كـ XLS باستخدام REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.fods",
      folder: "CellsTests",
      newfilename: "Book1Saveas.xls",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية حفظ FODS بتنسيق XLS باستخدام مكتبة Cloud NodeJS Cells." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة NodeJS وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في جافا سكريبت.</li>
<li>استخدم طريقة `PostWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>العقدة v6.17.1 أو الأحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
