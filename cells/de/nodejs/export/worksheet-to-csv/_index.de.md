---
title:  Exportieren Sie ARBEITSBLATT in CSV von Excel mit Cells Cloud SDK für NodeJS
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
kwords: Excel, worksheet, csv, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKSHEET to CSV","description": "How to use Cells Cloud SDK for Node to export objects from Excel WORKSHEET to CSV","image": {"@type": "ImageObject"},"url": "/nodejs/export/worksheet-to-csv/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKSHEET to CSV step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/worksheet-to-csv/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKSHEET to CSV step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/worksheet-to-csv/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKSHEET to CSV step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/worksheet-to-csv/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportieren Sie das Arbeitsblatt von Excel in CSV" h2="NodeJS-Bibliothek zum Exportieren von WORKSHEET in eine CSV-Datei" p="Verwenden Sie Export API von Cells Cloud, um interne Objektworkflows der Datei Excel in NodeJS zu exportieren. Dies ist eine professionelle Lösung zum Exportieren von ARBEITSBLÄTTEN in eine Datei im CSV-Format aus einer Tabellenkalkulation online mit NodeJS." urlsection="export/worksheet-to-csv/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportieren Sie das WORKSHEET-Objekt mit dem Cloud SDK Cells für NodeJS in eine Datei im CSV-Format" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren eines WORKSHEET-Objekts aus der Datei Excel in eine CSV-Datei ist eine komplexe Aufgabe. Übergänge zum Exportieren von WORKSHEET in das CSV-Format werden von unserem NodeJS SDK durchgeführt, während der strukturelle und logische Hauptinhalt der Quell-WORKSHEET-Tabelle erhalten bleibt. Unsere NodeJS-Bibliothek ist eine professionelle Lösung zum Online-Export von WORKSHEET-Objekten in Dateien im CSV-Format. Dieses Cloud SDK bietet NodeJS-Entwicklern leistungsstarke Funktionalität und perfekte CSV-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Codebeispiel in NodeJS mit REST API zum Exportieren von ARBEITSBLATT aus der Tabellenkalkulation in das CSV-Format" gistPath="" %}}
  
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
      objectType : "worksheet",
      format: "csv",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für Node, um Objekte aus Excel WORKSHEET in CSV zu exportieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `postExport`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Node v6.17.1 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
