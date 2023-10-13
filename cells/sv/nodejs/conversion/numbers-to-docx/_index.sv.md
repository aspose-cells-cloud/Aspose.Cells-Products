﻿---
title:  NUMBERS till DOCX Konvertera API för NodeJS
description:  Använda Aspose.Cells Cloud SDK för NodeJS för att konvertera NUMBERS-formatfil till DOCX-formatfil.
url: /sv/nodejs/conversion/numbers-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API för att konvertera NUMBERS till DOCX" h2="NodeJS-bibliotek för att konvertera NUMBERS till DOCX" p="Använd Cells Conversion REST API för att skapa anpassade kalkylbladsarbetsflöden i NodeJS. Detta är en professionell lösning för att konvertera NUMBERS till DOCX och andra dokumentformat online med NodeJS." urlsection="conversion/numbers-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera en NUMBERS-fil till DOCX i NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från NUMBERS till DOCX är en komplex uppgift. Alla NUMBERS- till DOCX-formatövergångar utförs av vår NodeJS SDK samtidigt som källarket NUMBERS-kalkylarkets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt NodeJS-bibliotek är en professionell lösning för att konvertera NUMBERS till DOCX-filer online. Denna Cloud SDK ger NodeJS-utvecklare kraftfull funktionalitet och perfekt DOCX-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i NodeJS med REST API för att konvertera NUMBERS till DOCX-format" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.numbers"),
        format: "docx",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Nod API för att konvertera NUMBERS till DOCX" >}}
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