---
title:  تحويل MHTML إلى TSV باستخدام NodeJS
description:  استخدام Aspose.Cells Cloud SDK لـ NodeJS لتحويل ملف بتنسيق MHTML إلى ملف بتنسيق TSV.
kwords: Excel, Convert MHTML to TSV, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert MHTML to TSV using the Cells Cloud NodeJS library.","description": "How to convert MHTML to TSV using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/conversion/mhtml-to-tsv/","step": [{ "@type": "HowToStep","name": "How to convert MHTML to TSV using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/mhtml-to-tsv/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert MHTML to TSV using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/mhtml-to-tsv/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert MHTML to TSV using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/mhtml-to-tsv/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to convert MHTML to TSV using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/mhtml-to-tsv/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل MHTML إلى TSV" h2="مكتبة NodeJS لتحويل MHTML إلى TSV" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع NodeJS. يعد هذا حلاً احترافيًا لتحويل MHTML إلى TSV وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام NodeJS." urlsection="conversion/mhtml-to-tsv/" >}}

{{< blocks/products/cells/cells-cloud-section title="قم بتحويل MHTML إلى TSV باستخدام Cells Cloud SDK لـ NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من MHTML إلى TSV مهمة معقدة. يتعامل NodeJS SDK الخاص بنا مع جميع تحويلات تنسيق MHTML إلى TSV مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات MHTML المصدر. توفر مكتبة NodeJS الخاصة بنا حلاً احترافيًا لتحويل ملفات MHTML إلى ملفات TSV عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري NodeJS بوظائف قوية ويضمن إخراج TSV عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على رمز NodeJS لتحويل MHTML إلى TSV باستخدام Cells Cloud SDK" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.mhtml"),
        format: "tsv",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية تحويل MHTML إلى TSV باستخدام مكتبة Cloud NodeJS Cells." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة NodeJS وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في جافا سكريبت.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>العقدة v6.17.1 أو الأحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
