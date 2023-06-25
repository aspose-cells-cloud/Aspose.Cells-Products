---
title: Save NUMBERS as TXT API for NodeJS 
description: Using Aspose.Cells Cloud SDK for NodeJS to save NUMBERS format file as TXT format file. 
url: /nodejs/saveas/numbers-to-txt/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API to save NUMBERS as TXT" h2="NodeJS library to save NUMBERS as TXT" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in NodeJS. This is a professional solution to save NUMBERS as TXT and other document formats online using NodeJS." urlsection="saveas/numbers-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a NUMBERS file as TXT in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from NUMBERS as TXT is a complex task. All NUMBERS to TXT format transitions is performed by our NodeJS SDK while maintaining the source NUMBERS spreadsheet's main structural and logical content. Our NodeJS library is a professional solution to save NUMBERS as TXT files online. This Cloud SDK gives NodeJS developers powerful functionality and perfect TXT output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in NodeJS using REST API to save NUMBERS as TXT format" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.numbers",
      folder: "CellsTests",
      newfilename: "Book1Saveas.txt",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Node API to save  NUMBERS as TXT" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cellsSaveAsPostDocumentSaveAs method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>node v6.17.1 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
