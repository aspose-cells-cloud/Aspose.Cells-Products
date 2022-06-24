---
title: Export Worksheet to GIF file via NodeJS
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Export workbok or interanl object to kinds of format file in the Cloud.
url: /nodejs/export/worksheet-to-gif/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Export Worksheet to GIF file in the Cloud" h2="Excel & OpenOffice spreadsheet export with open source Cloud SDK for NodeJS">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export Worksheet to GIF file in Cloud SDK for NodeJS " %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```LightCellsAPI``` with Client Id, Client Secret, Base URL & API version
1. Call ```postExport``` method to get the resultant GIF stream
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for .NET source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-node) to compile the SDK yourself or head to the [Releases](https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/releases) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/#/LightCells/PostExport) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="NodeJS Code for WORKSHEET to GIF Conversion" gistPath="" %}}
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
  objectType : "worksheet",
  format: "gif",
});
cellsApi.postExport(req)
  .then((result) => {
    let buff = new Buffer(result.body.files[0].fileContent, 'base64');
    fs.writeFileSync(result.body.files[0].filename, buff);
});
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{% blocks/products/cells/cells-cloud-api-run-export  InputFormat="xlsx;*.xls;*.csv;*.ods"  OutputFormat=gif  ExportObjectType=worksheet %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
