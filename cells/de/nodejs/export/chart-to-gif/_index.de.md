﻿---
title:  Exportieren Sie CHART in GIF aus der Tabelle mit NodeJS API
description: Aspose.Cells Cloud REST API unterstützt den Export von Excel Dateien und internen Objekten in Formatdateien. SDK unterstützt Arten von Entwicklungssprachen. Dazu gehören Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby und Swift.
url: /de/nodejs/export/chart-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API zum Exportieren von CHART in eine GIF-Datei" h2="NodeJS-Bibliothek zum Exportieren von CHART in eine GIF-Datei" p="Verwenden Sie Cells Export REST API, um Arbeitsabläufe für interne Tabellenkalkulationsobjekte in NodeJS zu exportieren. Dies ist eine professionelle Lösung zum Exportieren von CHART in eine Datei im GIF-Format aus einer Tabellenkalkulation online mit NodeJS." urlsection="export/chart-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exportieren Sie das CHART-Objekt in eine Datei im GIF-Format in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren eines CHART-Objekts in eine GIF-Datei aus einer Tabelle ist eine komplexe Aufgabe. Der Export von CHART in das GIF-Format wird von unserem NodeJS SDK durchgeführt, während der strukturelle und logische Hauptinhalt der CHART-Quelltabelle beibehalten wird. Unsere NodeJS-Bibliothek ist eine professionelle Lösung, um CHART-Objekte online in Dateien im GIF-Format zu exportieren. Dieses Cloud SDK bietet NodeJS-Entwicklern leistungsstarke Funktionen und eine perfekte GIF-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in NodeJS mit REST API zum Exportieren von CHART in das GIF-Format aus der Tabelle" gistPath="" %}}
  
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
      objectType : "chart",
      format: "gif",
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie den Knoten API, um CHART in GIF zu exportieren" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um kostenlose API Kontingent- und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und API-Version</li>
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