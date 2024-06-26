---
title:  تحويل TSV إلى SXC باستخدام NodeJS
description:  استخدام Aspose.Cells Cloud SDK لـ NodeJS لتحويل ملف بتنسيق TSV إلى ملف بتنسيق SXC.
kwords: Excel, Convert TSV to SXC, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert TSV to SXC using the Cells Cloud NodeJS library.","description": "How to convert TSV to SXC using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/conversion/tsv-to-sxc/","step": [{ "@type": "HowToStep","name": "How to convert TSV to SXC using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/tsv-to-sxc/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert TSV to SXC using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/tsv-to-sxc/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert TSV to SXC using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/tsv-to-sxc/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to convert TSV to SXC using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/tsv-to-sxc/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل TSV إلى SXC" h2="مكتبة NodeJS لتحويل TSV إلى SXC" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع NodeJS. يعد هذا حلاً احترافيًا لتحويل TSV إلى SXC وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام NodeJS." urlsection="conversion/tsv-to-sxc/" >}}

{{< blocks/products/cells/cells-cloud-section title="قم بتحويل TSV إلى SXC باستخدام Cells Cloud SDK لـ NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من TSV إلى SXC مهمة معقدة. يتعامل NodeJS SDK الخاص بنا مع جميع تحويلات تنسيق TSV إلى SXC مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات TSV المصدر. توفر مكتبة NodeJS الخاصة بنا حلاً احترافيًا لتحويل ملفات TSV إلى SXC عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري NodeJS بوظائف قوية ويضمن إخراج SXC عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على رمز NodeJS لتحويل TSV إلى SXC باستخدام Cells Cloud SDK" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.tsv"),
        format: "sxc",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية تحويل TSV إلى SXC باستخدام مكتبة Cloud NodeJS Cells." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة NodeJS وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في جافا سكريبت.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>العقدة v6.17.1 أو الأحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
