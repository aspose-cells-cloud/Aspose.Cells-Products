﻿---
title:  Spara MHTML som CSV API för C#
description:  Använder Aspose.Cells Cloud SDK för C# för att spara MHTML-formatfil som CSV-fil.
url: /sv/net/saveas/mhtml-to-csv/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API för att spara MHTML som CSV" h2="C# bibliotek för att spara MHTML som CSV" p="Använd Cells SaveAs REST API för att skapa anpassade kalkylbladsarbetsflöden i Net. Detta är en professionell lösning för att spara MHTML som CSV och andra dokumentformat online med C#." urlsection="saveas/mhtml-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en MHTML-fil som CSV i C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från MHTML som CSV är en komplex uppgift. Alla övergångar av MHTML till CSV-format utförs av vår C# SDK samtidigt som det huvudsakliga strukturella och logiska innehållet i MHTML-kalkylarket bibehålls. Vårt C#-bibliotek är en professionell lösning för att spara MHTML som CSV-filer online. Denna Cloud SDK ger C# utvecklare kraftfull funktionalitet och perfekt CSV-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i C# med REST API för att spara MHTML som CSV-format" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.mhtml";
    string newfilename = "Book1SaveAs.csv";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder C# API för att spara MHTML som CSV" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop CellsSaveAsPostDocumentSaveAs-metoden för att få den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>NET Framework 4.5.2 eller senare</li>
<li>Net Standard 2.0 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}