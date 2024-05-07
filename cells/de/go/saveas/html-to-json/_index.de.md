---
title:  Speichern Sie HTML als JSON mit Go
description:  Verwendung des Aspose.Cells Cloud SDK für Go zum Speichern der Datei im HTML-Format als JSON-Formatdatei.
kwords: Excel, Save HTML as JSON, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save HTML as JSON using the Cells Cloud Go library.","description": "How to save HTML as JSON using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/html-to-json/","step": [{ "@type": "HowToStep","name": "How to save HTML as JSON using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/html-to-json/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save HTML as JSON using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/html-to-json/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save HTML as JSON using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/html-to-json/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save HTML as JSON using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/html-to-json/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie HTML als JSON" h2="Gehen Sie zur Bibliothek, um HTML als JSON zu speichern" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Go zu erstellen. Dies ist eine professionelle Lösung zum Online-Speichern von HTML als JSON und anderen Dokumentformaten mit Go." urlsection="saveas/html-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine HTML-Datei als JSON in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten ab HTML als JSON ist eine komplexe Aufgabe. Alle Übergänge vom Format HTML zum JSON-Format werden von unserem Go SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quelltabelle HTML erhalten bleibt. Unsere Go-Bibliothek ist eine professionelle Lösung, um HTML als JSON-Dateien online zu speichern. Dieses Cloud SDK bietet Go-Entwicklern leistungsstarke Funktionalität und perfekte JSON-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go-Codebeispiel zum Speichern von HTML als JSON mit REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.html"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.json"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So speichern Sie HTML als JSON mit der Cells Cloud Go-Bibliothek." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Go-Bibliothek und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in go.</li>
<li>Verwenden Sie die Methode `PostWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Go-Version go1.13.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
