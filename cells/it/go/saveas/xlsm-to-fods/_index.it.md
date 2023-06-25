---
title:  Salva XLSM come FODS API per Go
description:  Utilizzo di Aspose.Cells Cloud SDK for Go per salvare il file in formato XLSM come file in formato FODS.
url: /it/go/saveas/xlsm-to-fods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Vai a API per salvare XLSM come FODS" h2="Vai in libreria per salvare XLSM come FODS" p="Utilizza Cells SaveAs REST API per creare flussi di lavoro di fogli di calcolo personalizzati in Go. Questa è una soluzione professionale per salvare XLSM come FODS e altri formati di documenti online utilizzando Go." urlsection="saveas/xlsm-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file XLSM come FODS in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Il salvataggio dei formati di file da XLSM come FODS è un compito complesso. Tutte le transizioni di formato da XLSM a FODS vengono eseguite dal nostro Go SDK mantenendo il principale contenuto strutturale e logico del foglio di calcolo XLSM di origine. La nostra libreria Go è una soluzione professionale per salvare XLSM come file FODS online. Questo Cloud SDK offre agli sviluppatori Go potenti funzionalità e un output FODS perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Go utilizzando REST API per salvare XLSM come formato FODS" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.xlsm"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.fods"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Go API per salvare XLSM come FODS" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiamare il metodo CellsSaveAsPostDocumentSaveAs per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>go versione go1.13.0 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
