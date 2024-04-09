---
title:  Converti HTML in XLT utilizzando Python
description:  Utilizzando Aspose.Cells Cloud SDK per Python per convertire un file in formato HTML in un file in formato XLT.
kwords: Excel, Convert HTML to XLT, REST, Python
howto: How to convert HTML to XLT using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti HTML in XLT" h2="Libreria Python per convertire HTML in XLT" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Python. Questa è una soluzione professionale per convertire HTML in XLT e altri formati di documenti online utilizzando Python." urlsection="conversion/html-to-xlt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti HTML in XLT utilizzando Cells Cloud SDK per Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da HTML a XLT può essere un compito complesso. Il nostro SDK Python gestisce tutte le conversioni dal formato HTML al formato XLT preservando il contenuto strutturale e logico principale del foglio di calcolo sorgente HTML. La nostra libreria Python fornisce una soluzione professionale per convertire online file HTML in XLT. Questo Cloud SDK offre agli sviluppatori Python potenti funzionalità e garantisce output XLT di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Esempio di codice per convertire HTML in XLT utilizzando Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.html",format="xlt")
    shutil.move(file1, "destFile.xlt")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Scopri come convertire HTML in XLT utilizzando la libreria Cells Cloud Python." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Python e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in Python.</li>
<li>Utilizza il metodo `put_convert_workbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Python 2.7 o successiva</li>
<li>Python 3.10 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
