---
title:  Speichern Sie MHTML als TXT mit Go
description:  Verwendung von Aspose.Cells Cloud SDK für Go zum Speichern von MHTML-Formatdateien als TXT-Formatdateien.
kwords: Excel, Save MHTML as TXT, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save MHTML as TXT using the Cells Cloud Go library.","description": "How to save MHTML as TXT using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/mhtml-to-txt/","step": [{ "@type": "HowToStep","name": "How to save MHTML as TXT using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/mhtml-to-txt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save MHTML as TXT using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/mhtml-to-txt/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save MHTML as TXT using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/mhtml-to-txt/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save MHTML as TXT using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/mhtml-to-txt/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie MHTML als TXT" h2="Go-Bibliothek zum Speichern von MHTML als TXT" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Go zu erstellen. Dies ist eine professionelle Lösung zum Online-Speichern von MHTML als TXT und anderen Dokumentformaten mit Go." urlsection="saveas/mhtml-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine MHTML-Datei als TXT in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten von MHTML als TXT ist eine komplexe Aufgabe. Alle Formatübergänge von MHTML zu TXT werden von unserem Go SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der MHTML-Quelltabelle erhalten bleibt. Unsere Go-Bibliothek ist eine professionelle Lösung zum Online-Speichern von MHTML als TXT-Dateien. Dieses Cloud SDK bietet Go-Entwicklern leistungsstarke Funktionen und eine perfekte TXT-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go-Codebeispiel zum Speichern von MHTML als TXT mit REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.mhtml"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.txt"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So speichern Sie MHTML als TXT mithilfe der Cloud Go-Bibliothek Cells." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Go-Bibliothek und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in go.</li>
<li>Verwenden Sie die Methode `PostWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Go-Version go1.13.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
