﻿---
title:  TSV-zu-MD-Konvertierung API für NodeJS
description:  Cloud-APIs und SDKs für Microsoft Excel und OpenOffice Calc. Konvertieren Sie die Tabelle in ein anderes Dateiformat.
url: /de/nodejs/conversion/tsv-to-md/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API zum Konvertieren von TSV in MD" h2="NodeJS-Bibliothek zum Konvertieren von TSV in MD" p="Verwenden Sie Cells Conversion REST API, um benutzerdefinierte Tabellenkalkulations-Workflows in NodeJS zu erstellen. Dies ist eine professionelle Lösung, um TSV online mit NodeJS in MD und andere Dokumentformate zu konvertieren." urlsection="conversion/tsv-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie eine TSV-Datei in MD in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von TSV in MD ist eine komplexe Aufgabe. Alle Formatübergänge von TSV zu MD werden von unserem NodeJS SDK durchgeführt, während der strukturelle und logische Hauptinhalt der TSV-Quelltabelle beibehalten wird. Unsere NodeJS-Bibliothek ist eine professionelle Lösung zur Online-Konvertierung von TSV- in MD-Dateien. Dieses Cloud SDK bietet NodeJS-Entwicklern leistungsstarke Funktionen und perfekte MD-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in NodeJS mit REST API zum Konvertieren von TSV in das MD-Format" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.tsv"),
        format: "md",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie den Knoten API, um TSV in MD zu konvertieren" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um kostenlose API Kontingent- und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und API-Version</li>
<li>Rufen Sie die Methode cellWorkbookPutConvertWorkbook auf, um den resultierenden Stream abzurufen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Knoten v6.17.1 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}