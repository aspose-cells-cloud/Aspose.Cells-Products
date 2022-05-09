---
title: Export Json to DOCX file via NodeJS
description: Aspose.Cells Cloud REST API support exporting Excel file and internal objects to kinds of format files. SDK support kinds of development languages. They include Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby, and swift.
url: /nodejs/export/json-to-docx/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Export JSON to  DOCX file in the Cloud" h2="Excel & OpenOffice spreadsheet export with open source Cloud SDK for NodeJS">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Exoprt JSON to DOCX file in Cloud SDK for NodeJS " %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApi``` with Client Id, Client Secret, Base URL & API version
1. Call ```cellsWorkbookPutConvertWorkbook``` method to get the resultant DOCX stream
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for .NET source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-node) to compile the SDK yourself or head to the [Releases](https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/releases) for alternative download options. 

Also have a look at Swagger-based [API Reference]() to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="NodeJS Code for JSON to DOCX Conversion" gistPath="" %}}
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
      file: fs.createReadStream(localPath + "datasource.xlsx"),
      format: "docx",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
      .then((result) => {
        console.log(result)
    });

```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
