---
title:  Speichern Sie FODS als DIF mit Go
description:  Verwendung von Aspose.Cells Cloud SDK für Go zum Speichern der FODS-Formatdatei als DIF-Formatdatei.
kwords: Excel, Save FODS as DIF, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save FODS as DIF using the Cells Cloud Go library.","description": "How to save FODS as DIF using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/fods-to-dif/","step": [{ "@type": "HowToStep","name": "How to save FODS as DIF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/fods-to-dif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save FODS as DIF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/fods-to-dif/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save FODS as DIF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/fods-to-dif/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save FODS as DIF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/fods-to-dif/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie FODS als DIF" h2="Go-Bibliothek zum Speichern von FODS als DIF" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Go zu erstellen. Dies ist eine professionelle Lösung zum Online-Speichern von FODS als DIF und anderen Dokumentformaten mit Go." urlsection="saveas/fods-to-dif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine FODS-Datei als DIF in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus FODS als DIF ist eine komplexe Aufgabe. Alle FODS-zu-DIF-Formatübergänge werden von unserem Go SDK durchgeführt, während die wichtigsten strukturellen und logischen Inhalte der Quell-FODS-Tabelle erhalten bleiben. Unsere Go-Bibliothek ist eine professionelle Lösung zum Online-Speichern von FODS als DIF-Dateien. Dieses Cloud SDK bietet Go-Entwicklern leistungsstarke Funktionalität und perfekte DIF-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go-Codebeispiel zum Speichern von FODS als DIF mit REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.fods"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.dif"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So speichern Sie FODS als DIF mithilfe der Cloud Go-Bibliothek Cells." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Go-Bibliothek und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in go.</li>
<li>Verwenden Sie die Methode `PostWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Go-Version go1.13.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
