---
title:  Exportieren Sie ARBEITSBLATT von Excel nach SVG mit dem Cloud SDK for Go Cells
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
kwords: Excel, worksheet, svg, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Go to export objects from Excel WORKSHEET to SVG","description": "How to use Cells Cloud SDK for Go to export objects from Excel WORKSHEET to SVG","image": {"@type": "ImageObject"},"url": "/go/export/worksheet-to-svg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel WORKSHEET to SVG step 1", "image": {"@type": "ImageObject",},"url": "/go/export/worksheet-to-svg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel WORKSHEET to SVG step 1", "image": {"@type": "ImageObject",},"url": "/go/export/worksheet-to-svg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel WORKSHEET to SVG step 1", "image": {"@type": "ImageObject",},"url": "/go/export/worksheet-to-svg/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportieren Sie das Arbeitsblatt von Excel nach SVG" h2="Go-Bibliothek zum Exportieren von WORKSHEET in die Datei SVG" p="Verwenden Sie Export API von Cells Cloud, um interne Objektworkflows der Datei Excel in Go zu exportieren. Dies ist eine professionelle Lösung zum Exportieren von WORKSHEET in eine Datei im SVG-Format aus einer Tabellenkalkulation online mit Go." urlsection="export/worksheet-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportieren Sie das WORKSHEET-Objekt mit dem Cloud SDK for Go Cells in eine Datei im Format SVG" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren eines WORKSHEET-Objekts aus der Datei Excel in die Datei SVG ist eine komplexe Aufgabe. Der Export von WORKSHEET in das SVG-Format wird von unserem Go SDK durchgeführt, während der strukturelle und logische Hauptinhalt der Quell-WORKSHEET-Tabelle erhalten bleibt. Unsere Go-Bibliothek ist eine professionelle Lösung zum Online-Export von WORKSHEET-Objekten in Dateien im Format SVG. Dieses Cloud SDK bietet Go-Entwicklern leistungsstarke Funktionalität und eine perfekte SVG-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Codebeispiel in Go mit REST API zum Exportieren von WORKSHEET in das SVG-Format aus der Tabellenkalkulation" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "encoding/base64"
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewLightCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    var files map[string]string
	    files = make(map[string]string)
	    files["Book1.xlsx"] = "C:/Book1.xlsx"
	    files["myDocument.xlsx"] = "C:/myDocument.xlsx"
	    postExportOpts := new(asposecellscloud.PostExportOpts)
	    postExportOpts.ObjectType = "worksheet"
	    postExportOpts.Format = "svg"
	    filesresult, _, err := instance.PostExport(files, postExportOpts)
	    if err != nil {
		    return
	    }
	    print(filesresult.Files[0].Filename)
	    originalStringBytes, err1 := base64.StdEncoding.DecodeString(filesresult.Files[0].FileContent)
	    if err1 != nil {
		    return
	    }
	    f, err2 := os.Create(filesresult.Files[0].Filename)
	    if err2 != nil {
		    return
	    }
	    _, err3 := f.Write(originalStringBytes)
	    if err3 != nil {
		    return
	    }
	    f.Close()
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für Go, um Objekte von Excel WORKSHEET nach SVG zu exportieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `postExport`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Go-Version go1.13.0 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
