---
title:  Salva TSV come XLSB utilizzando Go
description:  Utilizzando Aspose.Cells Cloud SDK per Go per salvare il file in formato TSV come file in formato XLSB.
kwords: Excel, Save TSV as XLSB, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save TSV as XLSB using the Cells Cloud Go library.","description": "How to save TSV as XLSB using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/tsv-to-xlsb/","step": [{ "@type": "HowToStep","name": "How to save TSV as XLSB using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/tsv-to-xlsb/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save TSV as XLSB using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/tsv-to-xlsb/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save TSV as XLSB using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/tsv-to-xlsb/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save TSV as XLSB using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/tsv-to-xlsb/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Salva TSV come XLSB" h2="Vai alla libreria per salvare TSV come XLSB" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo in Go. Questa è una soluzione professionale per salvare TSV come XLSB e altri formati di documenti online utilizzando Go." urlsection="saveas/tsv-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="Salva un file TSV come XLSB in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da TSV come XLSB è un compito complesso. Tutte le transizioni dal formato TSV al formato XLSB vengono eseguite dal nostro Go SDK mantenendo il contenuto strutturale e logico principale del foglio di calcolo TSV di origine. La nostra libreria Go è una soluzione professionale per salvare TSV come file XLSB online. Questo Cloud SDK offre agli sviluppatori Go funzionalità potenti e un output XLSB perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Vai ad esempio di codice per salvare TSV come XLSB utilizzando REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.tsv"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.xlsb"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come salvare TSV come XLSB utilizzando la libreria Cloud Go Cells." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Go e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in go.</li>
<li>Utilizza il metodo `PostWorkbookSaveAs` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>go versione go1.13.0 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
