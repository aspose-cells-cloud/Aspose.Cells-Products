﻿---
title:  NUMBERS in GIF Converti API per Python
description:  API cloud e SDK per Microsoft Excel e OpenOffice Calc. Converti foglio di calcolo in un altro file di formato.
url: /it/python/conversion/numbers-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API per convertire i NUMERI in GIF" h2="Python libreria per convertire NUMBERS in GIF" p="Usa Cells Conversion REST API per creare flussi di lavoro di fogli di calcolo personalizzati in Python. Questa è una soluzione professionale per convertire NUMBERS in GIF e altri formati di documenti online utilizzando Python." urlsection="conversion/numbers-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti un file NUMBERS in GIF in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da NUMBERS a GIF è un'attività complessa. Tutte le transizioni dal formato NUMBERS al formato GIF vengono eseguite dal nostro SDK Python mantenendo il contenuto strutturale e logico principale del foglio di calcolo NUMBERS sorgente. La nostra libreria Python è una soluzione professionale per convertire i NUMERI in file GIF online. Questo Cloud SDK offre agli sviluppatori Python potenti funzionalità e un output GIF perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Python utilizzando REST API per convertire NUMBERS in formato GIF" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.numbers",format="gif")
    shutil.move(file1, "destFile.gif")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Python API per convertire i NUMERI in GIF" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama celle_cartella di lavoro_Mettere_convertire_metodo della cartella di lavoro per ottenere il flusso risultante</li>
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