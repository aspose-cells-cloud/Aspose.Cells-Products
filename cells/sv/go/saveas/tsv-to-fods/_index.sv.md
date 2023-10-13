﻿---
title:  Spara TSV som FODS API för Go
description:  Använd Aspose.Cells Cloud SDK för Go för att spara TSV-formatfilen som FODS-formatfil.
url: /sv/go/saveas/tsv-to-fods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Gå API för att spara TSV som FODS" h2="Gå till biblioteket för att spara TSV som FODS" p="Använd Cells SaveAs REST API för att skapa anpassade kalkylbladsarbetsflöden i Go. Detta är en professionell lösning för att spara TSV som FODS och andra dokumentformat online med hjälp av Go." urlsection="saveas/tsv-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en TSV-fil som FODS i Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från TSV som FODS är en komplex uppgift. Alla TSV- till FODS-formatövergångar utförs av vår Go SDK samtidigt som käll-TSV-kalkylarkets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Go-bibliotek är en professionell lösning för att spara TSV som FODS-filer online. Denna Cloud SDK ger Go-utvecklare kraftfull funktionalitet och perfekt FODS-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Go med REST API för att spara TSV som FODS-format" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.tsv"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.fods"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Go API för att spara TSV som FODS" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop CellsSaveAsPostDocumentSaveAs-metoden för att få den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>go version go1.13.0 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}