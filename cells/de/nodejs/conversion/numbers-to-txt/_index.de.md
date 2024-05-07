---
title:  Konvertieren Sie NUMBERS mit NodeJS in TXT
description:  Verwendung des Cloud SDK Aspose.Cells für NodeJS zum Konvertieren einer Datei im NUMBERS-Format in eine Datei im TXT-Format.
kwords: Excel, Convert NUMBERS to TXT, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert NUMBERS to TXT using the Cells Cloud NodeJS library.","description": "How to convert NUMBERS to TXT using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/conversion/numbers-to-txt/","step": [{ "@type": "HowToStep","name": "How to convert NUMBERS to TXT using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/numbers-to-txt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert NUMBERS to TXT using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/numbers-to-txt/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert NUMBERS to TXT using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/numbers-to-txt/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to convert NUMBERS to TXT using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/numbers-to-txt/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie NUMBERS in TXT" h2="NodeJS-Bibliothek zum Konvertieren von NUMBERS in TXT" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in NodeJS-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von NUMBERS in TXT und andere Dokumentformate mit NodeJS." urlsection="conversion/numbers-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie NUMBERS mit dem Cloud SDK Cells für NodeJS in TXT" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von NUMBERS in TXT kann eine komplexe Aufgabe sein. Unser NodeJS SDK übernimmt alle Konvertierungen von NUMBERS in das TXT-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der NUMBERS-Quelltabelle bei. Unsere NodeJS-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von NUMBERS in TXT-Dateien. Dieses Cloud SDK bietet NodeJS-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige TXT-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="NodeJS-Codebeispiel für die Konvertierung von NUMBERS in TXT mit dem Cloud SDK Cells" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.numbers"),
        format: "txt",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So konvertieren Sie NUMBERS mithilfe der Cloud NodeJS-Bibliothek Cells in TXT." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die NodeJS-Bibliothek und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in JavaScript.</li>
<li>Verwenden Sie die Methode `putConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Node v6.17.1 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
