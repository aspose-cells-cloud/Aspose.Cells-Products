﻿---
title:  Spara NUMBERS som GIF med C#
description:  Använder Aspose.Cells Cloud SDK för C# för att spara NUMBERS-formatfilen som GIF-formatfil.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Spara NUMBERS som GIF" h2="C# bibliotek för att spara NUMBERS som GIF" p="Använd SaveAs API av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Net. Detta är en professionell lösning för att spara NUMBERS som GIF och andra dokumentformat online med C#." urlsection="saveas/numbers-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en NUMBERS-fil som GIF i C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från NUMBERS som GIF är en komplex uppgift. Alla NUMBERS- till GIF-formatövergångar utförs av vår C# SDK samtidigt som källarket NUMBERS-kalkylarkets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt C#-bibliotek är en professionell lösning för att spara NUMBERS som GIF-filer online. Denna Cloud SDK ger C# utvecklare kraftfull funktionalitet och perfekt GIF-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Kod Exempel för att spara NUMBERS som GIF med REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string newfilename = "Book1SaveAs.gif";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för Net för att spara Excel filer som andra format NUMBERS som GIF" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `PostWorkbookSaveAs` för att hämta den resulterande strömmen.</li>
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
