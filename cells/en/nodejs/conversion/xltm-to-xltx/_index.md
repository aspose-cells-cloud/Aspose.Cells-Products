---
title: XLTM to XLTX Convert API for NodeJS 
description: Using Aspose.Cells Cloud SDK for NodeJS to convert XLTM format file to XLTX format file. 
url: /nodejs/conversion/xltm-to-xltx/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API to convert XLTM to XLTX" h2="NodeJS library to convert XLTM to XLTX" p="Use Cells Conversion REST API to create customized spreadsheet workflows in NodeJS. This is a professional solution to convert XLTM to XLTX and other document formats online using NodeJS." urlsection="conversion/xltm-to-xltx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert a XLTM file to XLTX in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XLTM to XLTX is a complex task. All XLTM to XLTX format transitions is performed by our NodeJS SDK while maintaining the source XLTM spreadsheet's main structural and logical content. Our NodeJS library is a professional solution to convert XLTM to XLTX files online. This Cloud SDK gives NodeJS developers powerful functionality and perfect XLTX output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in NodeJS using REST API to convert XLTM to XLTX format" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xltm"),
        format: "xltx",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Node API to convert  XLTM to XLTX" >}}
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
