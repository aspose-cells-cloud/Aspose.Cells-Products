﻿---
title:  Exportieren Sie WORKBOOK nach PPTX von Excel mit Cells Cloud SDK für Python
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Exportieren Sie die Arbeitsmappe von Excel nach PPTX" h2="Python-Bibliothek zum Exportieren von WORKBOOK in eine PPTX-Datei" p="Verwenden Sie Export API von Cells Cloud, um Excel Datei-interne Objekt-Workflows in Python zu exportieren. Dies ist eine professionelle Lösung, um WORKBOOK online aus einer Tabellenkalkulation in eine PPTX-Formatdatei mit Python zu exportieren." urlsection="export/workbook-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exportieren Sie das WORKBOOK-Objekt in eine Datei im PPTX-Format mit dem Cloud SDK Cells für Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren eines WORKBOOK-Objekts aus der Datei Excel in eine PPTX-Datei ist eine komplexe Aufgabe. Übergänge beim Exportieren von WORKBOOK in das PPTX-Format werden von unserem SDK Python durchgeführt, während der Hauptstruktur- und logische Inhalt der Quell-WORKBOOK-Tabelle erhalten bleibt. Unsere Python-Bibliothek ist eine professionelle Lösung zum Online-Export von WORKBOOK-Objekten in PPTX-Formatdateien. Dieses Cloud SDK bietet Python Entwicklern leistungsstarke Funktionalität und perfekte PPTX-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in Python mit REST API zum Exportieren von WORKBOOK aus der Tabellenkalkulation in das PPTX-Format" gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"workbook","pptx")
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für Python, um Objekte aus Excel WORKBOOK nach PPTX zu exportieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Rufen Sie die Methode post_export auf, um den resultierenden Stream zu erhalten</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Python 2.7 oder neuer</li>
<li>Python 3.10 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
