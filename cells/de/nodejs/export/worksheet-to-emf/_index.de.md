---
title:  Exportieren Sie WORKSHEET aus der Tabelle mit NodeJS API nach EMF
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
url: /de/nodejs/export/worksheet-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API zum Exportieren von ARBEITSBLATT in die Datei EMF" h2="NodeJS-Bibliothek zum Exportieren von WORKSHEET in die Datei EMF" p="Verwenden Sie Cells Export REST API, um Arbeitsabläufe interner Tabellenkalkulationsobjekte in NodeJS zu exportieren. Dies ist eine professionelle Lösung zum Exportieren von WORKSHEET in eine Datei im Format EMF aus einer Tabellenkalkulation online mit NodeJS." urlsection="export/worksheet-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exportieren Sie das WORKSHEET-Objekt in die Formatdatei EMF in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren eines WORKSHEET-Objekts aus einer Tabellenkalkulation in die Datei EMF ist eine komplexe Aufgabe. Formatübergänge beim Exportieren von WORKSHEET in das EMF-Format werden von unserem NodeJS SDK durchgeführt, während der strukturelle und logische Hauptinhalt der Quell-WORKSHEET-Tabelle erhalten bleibt. Unsere NodeJS-Bibliothek ist eine professionelle Lösung zum Online-Export von WORKSHEET-Objekten in Dateien im Format EMF. Dieses Cloud SDK bietet NodeJS-Entwicklern leistungsstarke Funktionalität und eine perfekte EMF-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in NodeJS mit REST API zum Exportieren von WORKSHEET in das EMF-Format aus der Tabellenkalkulation" gistPath="" %}}
  
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
      format: "emf",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Knoten API, um ARBEITSBLATT nach EMF zu exportieren" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und Version API</li>
<li>Rufen Sie die Methode postExport auf, um den resultierenden Stream abzurufen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Knoten v6.17.1 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
