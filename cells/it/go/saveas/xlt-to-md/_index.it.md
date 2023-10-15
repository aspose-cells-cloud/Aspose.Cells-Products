---
title:  Salva XLT come MD utilizzando Go
description:  Utilizzando Aspose.Cells Cloud SDK per Go per salvare il file in formato XLT come file in formato MD.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Salva XLT come MD" h2="Vai alla libreria per salvare XLT come MD" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo in Go. Questa è una soluzione professionale per salvare XLT come MD e altri formati di documenti online utilizzando Go." urlsection="saveas/xlt-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file XLT come MD in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da XLT come MD è un compito complesso. Tutte le transizioni dal formato XLT al formato MD vengono eseguite dal nostro Go SDK mantenendo il contenuto strutturale e logico principale del foglio di calcolo XLT di origine. La nostra libreria Go è una soluzione professionale per salvare XLT come file MD online. Questo Cloud SDK offre agli sviluppatori Go funzionalità potenti e un output MD perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Go Code Esempio per salvare XLT come MD utilizzando REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.xlt"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.md"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK for Go per salvare i file Excel in altri formati XLT come MD" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `PostWorkbookSaveAs` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>go versione go1.13.0 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
