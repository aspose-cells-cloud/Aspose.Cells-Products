---
title:  Converti i NUMERI in MD utilizzando Python
description:  Utilizzando Aspose.Cells Cloud SDK per Python per convertire un file in formato NUMERI in un file in formato MD.
kwords: Excel, Convert NUMBERS to MD, REST, Python
howto: How to convert NUMBERS to MD using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti NUMERI in MD" h2="Libreria Python per la conversione dei NUMERI in MD" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Python. Questa è una soluzione professionale per convertire online NUMERI in MD e altri formati di documenti utilizzando Python." urlsection="conversion/numbers-to-md/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti NUMERI in MD utilizzando Cells Cloud SDK per Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da NUMBERS a MD può essere un compito complesso. Il nostro SDK Python gestisce tutte le conversioni dal formato NUMBERS al formato MD preservando il contenuto strutturale e logico principale del foglio di calcolo NUMBERS di origine. La nostra libreria Python fornisce una soluzione professionale per convertire online file NUMBERS in MD. Questo Cloud SDK offre agli sviluppatori Python potenti funzionalità e garantisce output MD di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Esempio di codice per convertire NUMERI in MD utilizzando Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.numbers",format="md")
    shutil.move(file1, "destFile.md")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Scopri come convertire NUMERI in MD utilizzando la libreria Cells Cloud Python." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Python e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in Python.</li>
<li>Utilizza il metodo `put_convert_workbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Python 2.7 o successiva</li>
<li>Python 3.10 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
