---
title:  Speichern Sie XLSB als GIF API für NodeJS
description: Verwenden Sie das Cloud SDK Aspose.Cells für NodeJS, um Dateien im XLSB-Format als GIF-Formatdateien zu speichern.
url: /de/nodejs/saveas/xlsb-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API zum Speichern von XLSB als GIF" h2="NodeJS-Bibliothek zum Speichern von XLSB als GIF" p="Verwenden Sie Cells SaveAs REST API, um benutzerdefinierte Tabellenkalkulations-Workflows in NodeJS zu erstellen. Dies ist eine professionelle Lösung zum Online-Speichern von XLSB als GIF und anderen Dokumentformaten mit NodeJS." urlsection="saveas/xlsb-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Speichern Sie eine XLSB-Datei als GIF in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten von XLSB als GIF ist eine komplexe Aufgabe. Alle XLSB-zu-GIF-Formatübergänge werden von unserem NodeJS SDK durchgeführt, während die wichtigsten strukturellen und logischen Inhalte der Quell-XLSB-Tabelle erhalten bleiben. Unsere NodeJS-Bibliothek ist eine professionelle Lösung, um XLSB als GIF-Dateien online zu speichern. Dieses Cloud SDK bietet NodeJS-Entwicklern leistungsstarke Funktionalität und perfekte GIF-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in NodeJS mit REST API zum Speichern von XLSB im GIF-Format" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xlsb",
      folder: "CellsTests",
      newfilename: "Book1Saveas.gif",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie den Knoten API, um XLSB als GIF zu speichern" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und Version API</li>
<li>Rufen Sie die Methode „cellsSaveAsPostDocumentSaveAs“ auf, um den resultierenden Stream abzurufen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Knoten v6.17.1 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
