---
title:  Esporta TABELLA a SVG da Excel utilizzando Cells Cloud SDK per Python
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Esporta TABELLA allo SVG da Excel" h2="Libreria Python per esportazione TABELLA nel file SVG" p="Utilizza Esporta API di Cells Cloud per esportare i flussi di lavoro degli oggetti interni del file Excel in Python. Questa è una soluzione professionale per esportare CHART nel file in formato SVG dal foglio di calcolo online utilizzando Python." urlsection="export/chart-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Esporta l\'oggetto CHART nel file in formato SVG utilizzando Cells Cloud SDK per Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto CHART nel file SVG dal file Excel è un'attività complessa. L'esportazione di CHART nelle transizioni del formato SVG viene eseguita dal nostro SDK Python mantenendo il contenuto strutturale e logico principale del foglio di calcolo CHART di origine. La nostra libreria Python è una soluzione professionale per esportare online oggetti CHART in file in formato SVG. Questo Cloud SDK offre agli sviluppatori Python funzionalità potenti e un output SVG perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Python utilizzando REST API per esportare GRAFICO nel formato SVG dal foglio di calcolo" gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"chart","svg")
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Python per esportare oggetti da Excel CHART a SVG" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Chiama il metodo post_export per ottenere il flusso risultante</li>
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
