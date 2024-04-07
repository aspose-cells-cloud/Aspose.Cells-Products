---
title: Export CHART to JPG from Excel using Cells Cloud SDK for NodeJS  
description: Aspose.Cells Cloud REST API support exporting {0} to {1} format files using {2}. 
kwords: 
howto: 
---


{{< blocks/products/cells/cells-cloud-banner h1="Export CHART to JPG from Excel" h2="NodeJS library for exporting CHART to JPG file" p="Use Export API of Cells Cloud to export Excel file internal object workflows in NodeJS. This is a professional solution to export CHART to JPG format file from spreadsheet online using NodeJS." urlsection="export/chart-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Export CHART object to JPG format file using Cells Cloud SDK for NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST %}}
<br/>
Export CHART object to JPG file from Excel file is a complex task. Export CHART to JPG format transitions is performed by our NodeJS SDK while maintaining the source CHART spreadsheet's main structural and logical content. Our NodeJS library is a professional solution to export CHART objects to JPG format files online. This Cloud SDK gives NodeJS developers powerful functionality and perfect JPG output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Code example in NodeJS using REST API to export CHART to JPG format from spreadsheet" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { LightCellsApi, PostExportRequest } = require("asposecellscloud");
    const localPath = "C:/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new LightCellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    const AssemblyTestXlsx = "assemblytest.xlsx";
    var dataAssemblyTestXlsx =fs.createReadStream(localPath  + AssemblyTestXlsx);
    const DataSourceXlsx = "datasource.xlsx";
    var dataDataSourceXlsx =fs.createReadStream(localPath  + DataSourceXlsx);
    var req = new PostExportRequest({
      file:{AssemblyTestXlsx:dataAssemblyTestXlsx ,DataSourceXlsx:dataDataSourceXlsx },
      objectType : "chart",
      format: "jpg",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Node to export objects from Excel CHART to JPG" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Use the `postExport` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>node v6.17.1 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
