---
title:  Exportera ARBETSBOK till EMF från Excel med Cells Cloud SDK för NodeJS
description:  Aspose.Cells Cloud REST API stöder export av filer från {0} till {1}-format med {2}.
kwords: Excel, workbook, emf, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to EMF","description": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to EMF","image": {"@type": "ImageObject"},"url": "/nodejs/export/workbook-to-emf/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to EMF step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/workbook-to-emf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to EMF step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/workbook-to-emf/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to EMF step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/workbook-to-emf/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportera ARBETSBOK till EMF från Excel" h2="NodeJS-bibliotek för export av WORKBOOK till EMF-fil" p="Använd Export API av Cells Cloud för att exportera Excel fil interna objekt arbetsflöden i NodeJS. Detta är en professionell lösning för att exportera ARBETSBOK till fil i formatet EMF från kalkylblad online med NodeJS." urlsection="export/workbook-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportera WORKBOOK-objekt till EMF-formatfil med Cells Cloud SDK för NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportera WORKBOOK-objekt till filen EMF från filen Excel är en komplex uppgift. Exportera WORKBOOK till EMF formatövergångar utförs av vår NodeJS SDK samtidigt som källarbetsbokens huvudsakliga strukturella och logiska innehåll bibehålls. Vårt NodeJS-bibliotek är en professionell lösning för att exportera WORKBOOK-objekt till EMF-formatfiler online. Denna Cloud SDK ger NodeJS-utvecklare kraftfull funktionalitet och perfekt EMF-utgång.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Kodexempel i NodeJS med REST API för att exportera ARBETSBOK till EMF-format från kalkylblad" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { LightCellsApi, PostExportRequest } = require("asposecellscloud");
    const localPath = "C:/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new LightCellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    const AssemblyTestXlsx = "assemblytest.xlsx";
    var dataAssemblyTestXlsx =fs.createReadStream(localPath  + AssemblyTestXlsx);
    const DataSourceXlsx = "datasource.xlsx";
    var dataDataSourceXlsx =fs.createReadStream(localPath  + DataSourceXlsx);
    var req = new PostExportRequest({
      file:{AssemblyTestXlsx:dataAssemblyTestXlsx ,DataSourceXlsx:dataDataSourceXlsx },
      objectType : "workbook",
      format: "emf",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för Node för att exportera objekt från Excel WORKBOOK till EMF" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `postExport` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>nod v6.17.1 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
