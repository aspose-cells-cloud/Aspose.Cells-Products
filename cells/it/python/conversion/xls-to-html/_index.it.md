---
title:  Converti XLS in HTML utilizzando Python
description:  Utilizzando Aspose.Cells Cloud SDK per Python per convertire un file in formato XLS in un file in formato HTML.
kwords: Excel, Convert XLS to HTML, REST, Python
howto: How to convert XLS to HTML using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti XLS in HTML" h2="Libreria Python per convertire XLS in HTML" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Python. Questa è una soluzione professionale per convertire XLS in HTML e altri formati di documenti online utilizzando Python." urlsection="conversion/xls-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti XLS in HTML utilizzando Cells Cloud SDK per Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da XLS a HTML può essere un compito complesso. Il nostro SDK Python gestisce tutte le conversioni del formato XLS in HTML preservando il contenuto strutturale e logico principale del foglio di calcolo XLS di origine. La nostra libreria Python fornisce una soluzione professionale per convertire file XLS in HTML online. Questo Cloud SDK offre agli sviluppatori Python potenti funzionalità e garantisce un output HTML di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Esempio di codice per convertire XLS in HTML utilizzando Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xls",format="html")
    shutil.move(file1, "destFile.html")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Scopri come convertire XLS in HTML utilizzando la libreria Cells Cloud Python." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Python e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in Python.</li>
<li>Utilizza il metodo `put_convert_workbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Python 2.7 o successiva</li>
<li>Python 3.10 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
