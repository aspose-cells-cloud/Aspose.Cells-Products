---
title:  Konvertieren Sie XLSM mit NodeJS in ODS
description:  Verwenden des Aspose.Cells Cloud SDK für NodeJS zum Konvertieren einer Datei im XLSM-Format in eine Datei im ODS-Format.
kwords: Excel, Convert XLSM to ODS, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLSM to ODS using the Cells Cloud NodeJS library.","description": "How to convert XLSM to ODS using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/conversion/xlsm-to-ods/","step": [{ "@type": "HowToStep","name": "How to convert XLSM to ODS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xlsm-to-ods/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLSM to ODS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xlsm-to-ods/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLSM to ODS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xlsm-to-ods/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to convert XLSM to ODS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xlsm-to-ods/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie XLSM in ODS" h2="NodeJS-Bibliothek zum Konvertieren von XLSM in ODS" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in NodeJS-Projekten zu erstellen. Dies ist eine professionelle Lösung, um XLSM online mit NodeJS in ODS und andere Dokumentformate zu konvertieren." urlsection="conversion/xlsm-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie XLSM in ODS mit Cells Cloud SDK für NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLSM in ODS kann eine komplexe Aufgabe sein. Unser NodeJS SDK übernimmt alle Konvertierungen von XLSM in das ODS-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der XLSM-Quelltabelle bei. Unsere NodeJS-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von XLSM- in ODS-Dateien. Dieses Cloud SDK stellt NodeJS-Entwicklern leistungsstarke Funktionen zur Verfügung und gewährleistet eine hochwertige ODS-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="NodeJS-Codebeispiel für die Konvertierung von XLSM in ODS mithilfe des Cloud SDK Cells" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xlsm"),
        format: "ods",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So konvertieren Sie XLSM mit der Cloud NodeJS-Bibliothek Cells in ODS." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die NodeJS-Bibliothek und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in JavaScript.</li>
<li>Verwenden Sie die Methode `putConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Node v6.17.1 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
