﻿---
title:  SXC till CSV Konvertera API för NodeJS
description:  Använder Aspose.Cells Cloud SDK för NodeJS för att konvertera fil i SXC-format till fil i CSV-format.
url: /sv/nodejs/conversion/sxc-to-csv/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API för att konvertera SXC till CSV" h2="NodeJS-bibliotek för att konvertera SXC till CSV" p="Använd Cells Conversion REST API för att skapa anpassade kalkylbladsarbetsflöden i NodeJS. Detta är en professionell lösning för att konvertera SXC till CSV och andra dokumentformat online med NodeJS." urlsection="conversion/sxc-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera en SXC-fil till CSV i NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från SXC till CSV är en komplex uppgift. Alla SXC- till CSV-formatövergångar utförs av vår NodeJS SDK samtidigt som käll-SXC-kalkylbladets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt NodeJS-bibliotek är en professionell lösning för att konvertera SXC till CSV-filer online. Denna Cloud SDK ger NodeJS-utvecklare kraftfull funktionalitet och perfekt CSV-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i NodeJS med REST API för att konvertera SXC till CSV-format" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.sxc"),
        format: "csv",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Node API för att konvertera SXC till CSV" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop cellsWorkbookPutConvertWorkbook-metoden för att få den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>nod v6.17.1 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}