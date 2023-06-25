---
title: MHTML to XLSM Convert API for NodeJS 
description: Using Aspose.Cells Cloud SDK for NodeJS to convert MHTML format file to XLSM format file. 
url: /nodejs/conversion/mhtml-to-xlsm/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API to convert MHTML to XLSM" h2="NodeJS library to convert MHTML to XLSM" p="Use Cells Conversion REST API to create customized spreadsheet workflows in NodeJS. This is a professional solution to convert MHTML to XLSM and other document formats online using NodeJS." urlsection="conversion/mhtml-to-xlsm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert a MHTML file to XLSM in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from MHTML to XLSM is a complex task. All MHTML to XLSM format transitions is performed by our NodeJS SDK while maintaining the source MHTML spreadsheet's main structural and logical content. Our NodeJS library is a professional solution to convert MHTML to XLSM files online. This Cloud SDK gives NodeJS developers powerful functionality and perfect XLSM output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in NodeJS using REST API to convert MHTML to XLSM format" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.mhtml"),
        format: "xlsm",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Node API to convert  MHTML to XLSM" >}}
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
