﻿---
title: MHTML till XPS Konvertera API till C#
description:  Använder Aspose.Cells Cloud SDK för C# för att konvertera fil i MHTML-format till fil i XPS-format.
url: /sv/net/conversion/mhtml-to-xps/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API för att konvertera MHTML till XPS" h2="C# bibliotek för att konvertera MHTML till XPS" p="Använd Cells Conversion REST API för att skapa anpassade arbetsflöden för kalkylblad i Net. Detta är en professionell lösning för att konvertera MHTML till XPS och andra dokumentformat online med C#." urlsection="conversion/mhtml-to-xps/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera en MHTML-fil till XPS i C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från MHTML till XPS är en komplex uppgift. Alla MHTML- till XPS-formatövergångar utförs av vår C# SDK samtidigt som Käll-MHTML-kalkylarkets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt C#-bibliotek är en professionell lösning för att konvertera MHTML till XPS-filer online. Denna Cloud SDK ger C#-utvecklare kraftfull funktionalitet och perfekt XPS-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i C# med REST API för att konvertera MHTML till XPS-format" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.mhtml";
    string format = "xps";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xps";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder C# API för att konvertera MHTML till XPS" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop CellsWorkbookPutConvertWorkbook-metoden för att få den resulterande strömmen</li>
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