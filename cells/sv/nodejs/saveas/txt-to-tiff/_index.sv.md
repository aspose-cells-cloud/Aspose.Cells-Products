﻿---
title:  Spara TXT som TIFF API för NodeJS
description: Använder Aspose.Cells Cloud SDK för NodeJS för att spara fil i TXT-format som fil i TIFF-format.
url: /sv/nodejs/saveas/txt-to-tiff/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API för att spara TXT som TIFF" h2="NodeJS-bibliotek för att spara TXT som TIFF" p="Använd Cells SaveAs REST API för att skapa anpassade kalkylbladsarbetsflöden i NodeJS. Detta är en professionell lösning för att spara TXT som TIFF och andra dokumentformat online med NodeJS." urlsection="saveas/txt-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en TXT-fil som TIFF i NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från TXT som TIFF är en komplex uppgift. Alla formatövergångar från TXT till TIFF utförs av vår NodeJS SDK samtidigt som källkodens TXT-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt NodeJS-bibliotek är en professionell lösning för att spara TXT som TIFF-filer online. Denna Cloud SDK ger NodeJS-utvecklare kraftfull funktionalitet och perfekt TIFF-utgång.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i NodeJS med REST API för att spara TXT som TIFF-format" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.txt",
      folder: "CellsTests",
      newfilename: "Book1Saveas.tiff",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Node API för att spara TXT som TIFF" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop cellsSaveAsPostDocumentSaveAs-metoden för att hämta den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>nod v6.17.1 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}