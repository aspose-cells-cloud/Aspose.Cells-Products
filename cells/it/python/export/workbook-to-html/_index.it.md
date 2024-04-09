---
title:  Esporta cartella di lavoro a HTML da Excel utilizzando Cells Cloud SDK per Python
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Esporta cartella di lavoro a HTML da Excel" h2="Libreria Python per esportare WORKBOOK nel file HTML" p="Utilizzare Esporta API di Cells Cloud per esportare i flussi di lavoro degli oggetti interni del file Excel in Python. Si tratta di una soluzione professionale per esportare la cartella di lavoro nel file in formato HTML dal foglio di calcolo online utilizzando Python." urlsection="export/workbook-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="Esporta l\'oggetto WORKBOOK nel file in formato HTML utilizzando Cells Cloud SDK per Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto WORKBOOK nel file HTML dal file Excel è un'attività complessa. L'esportazione della cartella di lavoro nelle transizioni del formato HTML viene eseguita dal nostro SDK Python mantenendo il contenuto strutturale e logico principale del foglio di calcolo della cartella di lavoro di origine. La nostra libreria Python è una soluzione professionale per esportare online oggetti WORKBOOK in file in formato HTML. Questo Cloud SDK offre agli sviluppatori Python funzionalità potenti e un output HTML perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice in Python utilizzando REST API per esportare WORKBOOK nel formato HTML dal foglio di calcolo" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import base64
    from asposecellscloud.apis.light_cells_api import LightCellsApi
    cells_api = LightCellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    files ={ 
        "myDocument.xlsx" :  "c:/myDocument.xlsx",
        "Book1.xlsx" :  "c:/Book1.xlsx" 
        }
    result = cells_api.post_export(files ,"workbook","html")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Python per esportare oggetti da Excel WORKBOOK a HTML" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Chiama il metodo post_export per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Python 2.7 o successiva</li>
<li>Python 3.10 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
