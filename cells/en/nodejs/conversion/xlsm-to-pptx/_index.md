---
title: XLSM to PPTX Convert API for NodeJS 
description: Using Aspose.Cells Cloud SDK for NodeJS to convert XLSM format file to PPTX format file. 
url: /nodejs/conversion/xlsm-to-pptx/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API to convert XLSM to PPTX" h2="NodeJS library to convert XLSM to PPTX" p="Use Cells Conversion REST API to create customized spreadsheet workflows in NodeJS. This is a professional solution to convert XLSM to PPTX and other document formats online using NodeJS." urlsection="conversion/xlsm-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert a XLSM file to PPTX in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XLSM to PPTX is a complex task. All XLSM to PPTX format transitions is performed by our NodeJS SDK while maintaining the source XLSM spreadsheet's main structural and logical content. Our NodeJS library is a professional solution to convert XLSM to PPTX files online. This Cloud SDK gives NodeJS developers powerful functionality and perfect PPTX output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in NodeJS using REST API to convert XLSM to PPTX format" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xlsm"),
        format: "pptx",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Node API to convert  XLSM to PPTX" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cellsWorkbookPutConvertWorkbook method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>node v6.17.1 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
