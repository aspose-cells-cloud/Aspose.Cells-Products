---
title:  Salva JPG come XLT utilizzando Python
description:  Utilizzando Aspose.Cells Cloud SDK per Python per salvare il file in formato JPG come file in formato XLT.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Salva JPG come XLT" h2="Libreria Python per salvare JPG come XLT" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati per fogli di calcolo in Python. Questa è una soluzione professionale per salvare JPG come XLT e altri formati di documenti online utilizzando Python." urlsection="saveas/jpg-to-xlt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file JPG come XLT in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da JPG come XLT è un compito complesso. Tutte le transizioni dal formato JPG al formato XLT vengono eseguite dal nostro SDK Python mantenendo il contenuto strutturale e logico principale del foglio di calcolo JPG di origine. La nostra libreria Python è una soluzione professionale per salvare JPG come file XLT online. Questo Cloud SDK offre agli sviluppatori Python funzionalità potenti e un output XLT perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Codice Esempio per salvare JPG come XLT utilizzando REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.jpg'    
    saveOptions = None
    newfilename = "Book1Saveas.xlt"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Python per salvare i file Excel in altri formati JPG come XLT" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `post_workbook_save_as` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Python 2.7 o successiva</li>
<li>Python 3.10 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
