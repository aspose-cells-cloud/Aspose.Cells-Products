---
title:  Speichern Sie SXC als FODS mit NodeJS
description:  Verwendung von Aspose.Cells Cloud SDK für NodeJS zum Speichern von SXC-Formatdateien als FODS-Formatdateien.
kwords: Excel, Save SXC as FODS, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save SXC as FODS using the Cells Cloud NodeJS library.","description": "How to save SXC as FODS using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/saveas/sxc-to-fods/","step": [{ "@type": "HowToStep","name": "How to save SXC as FODS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/sxc-to-fods/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save SXC as FODS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/sxc-to-fods/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save SXC as FODS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/sxc-to-fods/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to save SXC as FODS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/sxc-to-fods/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie SXC als FODS" h2="NodeJS-Bibliothek zum Speichern von SXC als FODS" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in NodeJS zu erstellen. Dies ist eine professionelle Lösung zum Online-Speichern von SXC als FODS und anderen Dokumentformaten mit NodeJS." urlsection="saveas/sxc-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine SXC-Datei als FODS in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus SXC als FODS ist eine komplexe Aufgabe. Alle SXC-zu-FODS-Formatübergänge werden von unserem NodeJS SDK durchgeführt, während der strukturelle und logische Hauptinhalt der Quell-SXC-Tabelle erhalten bleibt. Unsere NodeJS-Bibliothek ist eine professionelle Lösung, um SXC als FODS-Dateien online zu speichern. Dieses Cloud SDK bietet NodeJS-Entwicklern leistungsstarke Funktionalität und perfekte FODS-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="NodeJS-Codebeispiel zum Speichern von SXC als FODS mit REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.sxc",
      folder: "CellsTests",
      newfilename: "Book1Saveas.fods",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So speichern Sie SXC als FODS mithilfe der Cloud NodeJS-Bibliothek Cells." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die NodeJS-Bibliothek und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in JavaScript.</li>
<li>Verwenden Sie die Methode `PostWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Node v6.17.1 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
