---
title:  Converti PNG in PDF utilizzando Python
description:  Utilizzando Aspose.Cells Cloud SDK per Python per convertire un file in formato PNG in un file in formato PDF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertire PNG in PDF" h2="Libreria Python per convertire PNG in PDF" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Python. Questa è una soluzione professionale per convertire PNG in PDF e altri formati di documenti online utilizzando Python." urlsection="conversion/png-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti PNG in PDF utilizzando Cells Cloud SDK per Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da PNG a PDF può essere un compito complesso. Il nostro SDK Python gestisce tutte le conversioni del formato da PNG a PDF preservando il contenuto strutturale e logico principale del foglio di calcolo di origine PNG. La nostra libreria Python fornisce una soluzione professionale per convertire i file PNG in PDF online. Questo Cloud SDK offre agli sviluppatori Python potenti funzionalità e garantisce un output PDF di alta qualità.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Esempio di codice per convertire PNG in PDF utilizzando Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.png",format="pdf")
    shutil.move(file1, "destFile.pdf")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Python per convertire i file Excel in altri formati da PNG a PDF" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `put_convert_workbook` per recuperare il flusso risultante.</li>
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
