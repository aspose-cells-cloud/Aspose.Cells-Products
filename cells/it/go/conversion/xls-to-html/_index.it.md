---
title:  Converti XLS in HTML utilizzando Go
description: Utilizzando Aspose.Cells Cloud SDK for Go per convertire un file in formato XLS in un file in formato HTML.
kwords: Excel, Convert XLS to HTML, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLS to HTML using the Cells Cloud Go library.","description": "How to convert XLS to HTML using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/conversion/xls-to-html/","step": [{ "@type": "HowToStep","name": "How to convert XLS to HTML using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/xls-to-html/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLS to HTML using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/xls-to-html/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLS to HTML using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/xls-to-html/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to convert XLS to HTML using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/xls-to-html/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti XLS in HTML" h2="Vai alla libreria per convertire XLS in HTML" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Go. Questa è una soluzione professionale per convertire XLS in HTML e altri formati di documenti online utilizzando Go." urlsection="conversion/xls-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti XLS in HTML utilizzando Cells Cloud SDK per Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da XLS a HTML può essere un compito complesso. Il nostro Go SDK gestisce tutte le conversioni del formato XLS in HTML preservando il contenuto strutturale e logico principale del foglio di calcolo XLS di origine. La nostra libreria Go fornisce una soluzione professionale per convertire file XLS in HTML online. Questo Cloud SDK offre agli sviluppatori Go funzionalità potenti e garantisce un output HTML di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio Go Code per convertire XLS in HTML utilizzando Cells Cloud SDK" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.xls")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "html"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.html")
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come convertire XLS in HTML utilizzando la libreria Cloud Go Cells." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Go e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in go.</li>
<li>Utilizza il metodo `PutConvertWorkbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>go versione go1.13.0 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
