---
title: Convert XLS to DOCX using NodeJS 
description: Utilizing the Aspose.Cells Cloud SDK for NodeJS to convert a XLS format file to a DOCX format file. 
kwords: Excel, Convert XLS to DOCX, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLS to DOCX using the Cells Cloud NodeJS library.","description": "How to convert XLS to DOCX using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/conversion/xls-to-docx/","step": [{ "@type": "HowToStep","name": "How to convert XLS to DOCX using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xls-to-docx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLS to DOCX using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xls-to-docx/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLS to DOCX using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xls-to-docx/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to convert XLS to DOCX using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xls-to-docx/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert XLS to DOCX" h2="NodeJS library for converting XLS to DOCX" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in NodeJS projects. This is a professional solution to convert XLS to DOCX and other document formats online using NodeJS." urlsection="conversion/xls-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert XLS to DOCX using Cells Cloud SDK for NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XLS to DOCX can be a complex task. Our NodeJS SDK handles all XLS to DOCX format conversions while preserving the main structural and logical content of the source XLS spreadsheet. Our NodeJS library provides a professional solution for converting XLS to DOCX files online. This Cloud SDK empowers NodeJS developers with powerful functionality and ensures high-quality DOCX output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="NodeJS Code Example for converting XLS to DOCX using Cells Cloud SDK" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xls"),
        format: "docx",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to convert XLS to DOCX using the Cells Cloud NodeJS library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install NodeJS library and add the reference (import the library) to your project.</li>
<li>Open the source file in JavaScript.</li>
<li>Use the `putConvertWorkbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>node v6.17.1 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
