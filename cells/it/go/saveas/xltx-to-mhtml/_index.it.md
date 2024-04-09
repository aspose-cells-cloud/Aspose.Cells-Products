---
title:  Salva XLTX come MHTML utilizzando Go
description:  Utilizzando Aspose.Cells Cloud SDK per Go per salvare il file in formato XLTX come file in formato MHTML.
kwords: Excel, Save XLTX as MHTML, REST, Go
howto: How to save XLTX as MHTML using Aspose.Cells Cloud Go library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Salva XLTX come MHTML" h2="Vai alla libreria per salvare XLTX come MHTML" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo in Go. Questa è una soluzione professionale per salvare XLTX come MHTML e altri formati di documenti online utilizzando Go." urlsection="saveas/xltx-to-mhtml/" >}}

{{< blocks/products/cells/cells-cloud-section title="Salva un file XLTX come MHTML in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da XLTX come MHTML è un compito complesso. Tutte le transizioni dal formato XLTX al formato MHTML vengono eseguite dal nostro Go SDK mantenendo il contenuto strutturale e logico principale del foglio di calcolo XLTX di origine. La nostra libreria Go è una soluzione professionale per salvare XLTX come file MHTML online. Questo Cloud SDK offre agli sviluppatori Go funzionalità potenti e un output MHTML perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Vai ad esempio di codice per salvare XLTX come MHTML utilizzando REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.xltx"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.mhtml"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Scopri come salvare XLTX come MHTML utilizzando la libreria Cloud Go Cells." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Go e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in go.</li>
<li>Utilizza il metodo `PostWorkbookSaveAs` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>go versione go1.13.0 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
