---
title:  Konvertieren Sie TXT mit Go in XLS
description: Verwendung des Cloud SDK Aspose.Cells für Go zum Konvertieren einer Datei im TXT-Format in eine Datei im XLS-Format.
kwords: Excel, Convert TXT to XLS, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert TXT to XLS using the Cells Cloud Go library.","description": "How to convert TXT to XLS using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/conversion/txt-to-xls/","step": [{ "@type": "HowToStep","name": "How to convert TXT to XLS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/txt-to-xls/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert TXT to XLS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/txt-to-xls/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert TXT to XLS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/txt-to-xls/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to convert TXT to XLS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/txt-to-xls/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie TXT in XLS" h2="Go-Bibliothek zum Konvertieren von TXT in XLS" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Go-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von TXT in XLS und andere Dokumentformate mit Go." urlsection="conversion/txt-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie TXT in XLS mit dem Cloud SDK Cells für Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von TXT in XLS kann eine komplexe Aufgabe sein. Unser Go SDK verarbeitet alle TXT-in-XLS-Formatkonvertierungen und behält dabei den wichtigsten strukturellen und logischen Inhalt der TXT-Quelltabelle bei. Unsere Go-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von TXT- in XLS-Dateien. Dieses Cloud SDK bietet Go-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige XLS-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go-Codebeispiel für die Konvertierung von TXT in XLS mit dem Cloud SDK Cells" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.txt")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "xls"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.xls")
	    if err2 != nil {
		    return
	    }
	    if _, err3 := file1.Write(value); err3 != nil {
		    return
	    }
	    file1.Close()
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So konvertieren Sie TXT mit der Cloud Go-Bibliothek Cells in XLS." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Go-Bibliothek und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in go.</li>
<li>Verwenden Sie die Methode `PutConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Go-Version go1.13.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
