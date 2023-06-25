---
title:  Esporta LISTOBJECT in TIFF dal foglio di calcolo utilizzando Python API
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
url: /it/python/export/listobject-to-tiff/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API per esportare LISTOBJECT nel file TIFF" h2="Python libreria per esportare LISTOBJECT nel file TIFF" p="Utilizzare Cells Esporta REST API per esportare i flussi di lavoro degli oggetti interni del foglio di calcolo in Python. Questa è una soluzione professionale per esportare LISTOBJECT in un file in formato TIFF dal foglio di calcolo online utilizzando Python." urlsection="export/listobject-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Esporta l\'oggetto LISTOBJECT nel file di formato TIFF in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto LISTOBJECT nel file TIFF dal foglio di calcolo è un'attività complessa. L'esportazione delle transizioni di formato da LISTOBJECT a TIFF viene eseguita dal nostro SDK Python mantenendo il contenuto strutturale e logico principale del foglio di calcolo LISTOBJECT di origine. La nostra libreria Python è una soluzione professionale per esportare oggetti LISTOBJECT in file in formato TIFF online. Questo Cloud SDK offre agli sviluppatori Python potenti funzionalità e un output TIFF perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Python utilizzando REST API per esportare LISTOBJECT nel formato TIFF dal foglio di calcolo" gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"listobject","tiff")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Python API per esportare LISTOBJECT in TIFF" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo post_export per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Python 2.7 o più recente</li>
<li>Python 3.10 o più recente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
