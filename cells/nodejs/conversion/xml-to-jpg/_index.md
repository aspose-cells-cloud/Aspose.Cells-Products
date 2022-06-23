---
title: Convert XML to JPG via NodeJS
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Create, Edit, Render or Convert spreadsheet in the Cloud.
url: /nodejs/conversion/xml-to-jpg/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XML to  JPG in the Cloud" h2="Excel & OpenOffice spreadsheet conversion with open source Cloud SDK for NodeJS">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XML to JPG Conversion in Cloud SDK for NodeJS " %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApi``` with Client Id, Client Secret, Base URL & API version
1. Call ```cellsWorkbookPutConvertWorkbook``` method to get the resultant JPG stream
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for .NET source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-node) to compile the SDK yourself or head to the [Releases](https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/releases) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="NodeJS Code for XML to JPG Conversion" gistPath="" %}}
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
      file: fs.createReadStream(localPath + "datasource.xml"),
      format: "jpg",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
      .then((result) => {
        console.log(result)
    });

```

{{% /blocks/products/pf/agp/code-autogen %}}
{{% blocks/products/cells/cells-cloud-api-run-conversion  inputformat=xml  outputformat=jpg  %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
