---
title:  Konvertera PNG till HTML med NodeJS
description:  Använda Aspose.Cells Cloud SDK för NodeJS för att konvertera en fil i PNG-format till en fil i HTML-format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertera PNG till HTML" h2="NodeJS-bibliotek för att konvertera PNG till HTML" p="Använd Conversion API of of Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i NodeJS-projekt. Detta är en professionell lösning för att konvertera PNG till HTML och andra dokumentformat online med NodeJS." urlsection="conversion/png-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera PNG till HTML med Cells Cloud SDK för NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från PNG till HTML kan vara en komplicerad uppgift. Vår NodeJS SDK hanterar alla formatkonverteringar från PNG till HTML samtidigt som det huvudsakliga strukturella och logiska innehållet i källarket PNG bevaras. Vårt NodeJS-bibliotek tillhandahåller en professionell lösning för att konvertera PNG till HTML filer online. Denna Cloud SDK ger NodeJS-utvecklare kraftfull funktionalitet och säkerställer högkvalitativa HTML-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="NodeJS-kodexempel för att konvertera PNG till HTML med Cells Cloud SDK" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.png"),
        format: "html",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Så här använder du Cells Cloud SDK för Node för att konvertera Excel-filer till andra format PNG till HTML" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `putConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>nod v6.17.1 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
