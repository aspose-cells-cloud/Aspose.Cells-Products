---
title: Save XLT as SXC using NodeJS 
description: Utilizing Aspose.Cells Cloud SDK for NodeJS to save XLT format file as SXC format file. 
kwords: Excel, Save XLT as SXC, REST, NodeJS
howto: How to save XLT as SXC using Aspose.Cells Cloud NodeJS library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save XLT as SXC" h2="NodeJS library for saving XLT as SXC" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in NodeJS. This is a professional solution to save XLT as SXC and other document formats online using NodeJS." urlsection="saveas/xlt-to-sxc/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a XLT file as SXC in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLT as SXC is a complex task. All XLT to SXC format transitions is performed by our NodeJS SDK while maintaining the source XLT spreadsheet's main structural and logical content. Our NodeJS library is a professional solution to save XLT as SXC files online. This Cloud SDK gives NodeJS developers powerful functionality and perfect SXC output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="NodeJS Code Example for saving XLT as SXC using REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xlt",
      folder: "CellsTests",
      newfilename: "Book1Saveas.sxc",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save XLT as SXC using the Cells Cloud NodeJS library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install NodeJS library and add the reference (import the library) to your project.</li>
<li>Open the source file in JavaScript.</li>
<li>Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>node v6.17.1 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
