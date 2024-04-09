---
title:  Converti i NUMERI in TIFF usando Go
description:  Utilizzando Aspose.Cells Cloud SDK for Go per convertire un file in formato NUMBERS in un file in formato TIFF.
kwords: Excel, Convert NUMBERS to TIFF, REST, Go
howto: How to convert NUMBERS to TIFF using Aspose.Cells Cloud Go library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti i NUMERI in TIFF" h2="Vai alla libreria per convertire i NUMERI in TIFF" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Go. Questa è una soluzione professionale per convertire i NUMERI in TIFF e altri formati di documenti online utilizzando Go." urlsection="conversion/numbers-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti NUMERI in TIFF utilizzando Cells Cloud SDK per Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da NUMBERS a TIFF può essere un compito complesso. Il nostro Go SDK gestisce tutte le conversioni del formato NUMBERS in TIFF preservando il contenuto strutturale e logico principale del foglio di calcolo NUMBERS di origine. La nostra libreria Go fornisce una soluzione professionale per convertire online i file NUMBERS in TIFF. Questo Cloud SDK offre agli sviluppatori Go funzionalità potenti e garantisce un output TIFF di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio Go Code per convertire NUMERI in TIFF utilizzando Cells Cloud SDK" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.numbers")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "tiff"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.tiff")
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Scopri come convertire i NUMERI in TIFF utilizzando la libreria Cells Cloud Go." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Go e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in go.</li>
<li>Utilizza il metodo `PutConvertWorkbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>go versione go1.13.0 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
