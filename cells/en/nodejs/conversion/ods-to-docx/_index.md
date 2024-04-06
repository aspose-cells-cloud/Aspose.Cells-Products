---
title: Convert ODS to DOCX using NodeJS 
description: Utilizing the Aspose.Cells Cloud SDK for NodeJS to convert a ODS format file to a DOCX format file. 
kwords: Excel, Convert ODS to DOCX, REST, NodeJS
howto: How to convert ODS to DOCX using Aspose.Cells Cloud NodeJS library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert ODS to DOCX" h2="NodeJS library for converting ODS to DOCX" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in NodeJS projects. This is a professional solution to convert ODS to DOCX and other document formats online using NodeJS." urlsection="conversion/ods-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert ODS to DOCX using Cells Cloud SDK for NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from ODS to DOCX can be a complex task. Our NodeJS SDK handles all ODS to DOCX format conversions while preserving the main structural and logical content of the source ODS spreadsheet. Our NodeJS library provides a professional solution for converting ODS to DOCX files online. This Cloud SDK empowers NodeJS developers with powerful functionality and ensures high-quality DOCX output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="NodeJS Code Example for converting ODS to DOCX using Cells Cloud SDK" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.ods"),
        format: "docx",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to convert ODS to DOCX using the Cells Cloud NodeJS library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install NodeJS library and add the reference (import the library) to your project.</li>
<li>Open the source file in JavaScript.</li>
<li>Use the `putConvertWorkbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>node v6.17.1 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
