﻿---
title:  Spara HTML som EMF API för C#
description: Använd Aspose.Cells Cloud SDK för C# för att spara HTML filformat som EMF filformat.
url: /sv/net/saveas/html-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API för att spara HTML som EMF" h2="C# bibliotek för att spara HTML som EMF" p="Använd Cells SaveAs REST API för att skapa anpassade kalkylbladsarbetsflöden i Net. Detta är en professionell lösning för att spara HTML som EMF och andra dokumentformat online med C#." urlsection="saveas/html-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en HTML-fil som EMF i C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från HTML som EMF är en komplex uppgift. Alla formatövergångar från HTML till EMF utförs av vår C# SDK samtidigt som källbladets HTML kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt C#-bibliotek är en professionell lösning för att spara HTML som EMF-filer online. Denna Cloud SDK ger C# utvecklare kraftfull funktionalitet och perfekt EMF utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i C# med REST API för att spara HTML som EMF-format" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.html";
    string newfilename = "Book1SaveAs.emf";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder C# API för att spara HTML som EMF" >}}
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