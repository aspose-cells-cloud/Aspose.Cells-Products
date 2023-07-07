---
title:  XLSX zu XLSM Konvertieren API für NodeJS
description:  Verwenden von Aspose.Cells Cloud SDK für NodeJS zum Konvertieren einer Datei im XLSX-Format in eine Datei im XLSM-Format.
url: /de/nodejs/conversion/xlsx-to-xlsm/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API zum Konvertieren von XLSX in XLSM" h2="NodeJS-Bibliothek zum Konvertieren von XLSX in XLSM" p="Verwenden Sie Cells Conversion REST API, um benutzerdefinierte Tabellenkalkulations-Workflows in NodeJS zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XLSX in XLSM und andere Dokumentformate mit NodeJS." urlsection="conversion/xlsx-to-xlsm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie eine XLSX-Datei in XLSM in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLSX in XLSM ist eine komplexe Aufgabe. Alle XLSX-zu-XLSM-Formatübergänge werden von unserem NodeJS SDK durchgeführt, während der wichtigste strukturelle und logische Inhalt der XLSX-Quelltabelle erhalten bleibt. Unsere NodeJS-Bibliothek ist eine professionelle Lösung zum Online-Konvertieren von XLSX- in XLSM-Dateien. Dieses Cloud SDK bietet NodeJS-Entwicklern leistungsstarke Funktionalität und perfekte XLSM-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in NodeJS mit REST API zum Konvertieren von XLSX in das XLSM-Format" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xlsx"),
        format: "xlsm",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie den Knoten API zum Konvertieren von XLSX in XLSM" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und Version API</li>
<li>Rufen Sie die Methode „cellsWorkbookPutConvertWorkbook“ auf, um den resultierenden Stream abzurufen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Knoten v6.17.1 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
