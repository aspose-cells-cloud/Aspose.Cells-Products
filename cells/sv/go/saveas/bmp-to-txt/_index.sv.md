﻿---
title:  Spara BMP som TXT API för Go
description:  Använd Aspose.Cells Cloud SDK för Go för att spara BMP filformat som TXT-formatfil.
url: /sv/go/saveas/bmp-to-txt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Gå till API för att spara BMP som TXT" h2="Gå till biblioteket för att spara BMP som TXT" p="Använd Cells SaveAs REST API för att skapa anpassade kalkylbladsarbetsflöden i Go. Detta är en professionell lösning för att spara BMP som TXT och andra dokumentformat online med Go." urlsection="saveas/bmp-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en BMP-fil som TXT i Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från BMP som TXT är en komplex uppgift. Alla formatövergångar från BMP till TXT utförs av vår Go SDK samtidigt som källbladets BMP kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Go-bibliotek är en professionell lösning för att spara BMP som TXT-filer online. Denna Cloud SDK ger Go-utvecklare kraftfull funktionalitet och perfekt TXT-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Go med REST API för att spara BMP som TXT-format" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.bmp"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.txt"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Go API för att spara BMP som TXT" >}}
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