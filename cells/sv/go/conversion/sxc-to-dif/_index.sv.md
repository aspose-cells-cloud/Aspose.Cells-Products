﻿---
title:  SXC till DIF Konvertera API för Go
description:  Använd Aspose.Cells Cloud SDK för Go för att konvertera fil i SXC-format till fil i DIF-format.
url: /sv/go/conversion/sxc-to-dif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Gå API för att konvertera SXC till DIF" h2="Gå till biblioteket för att konvertera SXC till DIF" p="Använd Cells Conversion REST API för att skapa anpassade kalkylbladsarbetsflöden i Go. Detta är en professionell lösning för att konvertera SXC till DIF och andra dokumentformat online med Go." urlsection="conversion/sxc-to-dif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera en SXC-fil till DIF i Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från SXC till DIF är en komplex uppgift. Alla SXC- till DIF-formatövergångar utförs av vår Go SDK samtidigt som käll-SXC-kalkylbladets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Go-bibliotek är en professionell lösning för att konvertera SXC till DIF-filer online. Denna Cloud SDK ger Go-utvecklare kraftfull funktionalitet och perfekt DIF-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Go med REST API för att konvertera SXC till DIF-format" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.sxc")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "dif"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.dif")
	    if err2 != nil {
		    return
	    }
	    if _, err3 := file1.Write(value); err3 != nil {
		    return
	    }
	    file1.Close()
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Go API för att konvertera SXC till DIF" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop CellsWorkbookPutConvertWorkbook-metoden för att få den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>go version go1.13.0 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}