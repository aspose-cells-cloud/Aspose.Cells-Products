---
title:  Konvertieren Sie TSV in FODS mit Python
description:  Verwendung des Aspose.Cells Cloud SDK für Python zum Konvertieren einer TSV-Formatdatei in eine FODS-Formatdatei.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertieren Sie TSV in FODS" h2="Python Bibliothek zur Konvertierung von TSV in FODS" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Python-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von TSV in FODS und andere Dokumentformate unter Python." urlsection="conversion/tsv-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie TSV in FODS mit dem Cloud SDK Cells für Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von TSV in FODS kann eine komplexe Aufgabe sein. Unser Python SDK übernimmt alle TSV-in-FODS-Formatkonvertierungen und behält dabei den wichtigsten strukturellen und logischen Inhalt der TSV-Quelltabelle bei. Unsere Python-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von TSV- in FODS-Dateien. Dieses Cloud SDK bietet Python-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige FODS-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Codebeispiel für die Konvertierung von TSV in FODS mit Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.tsv",format="fods")
    shutil.move(file1, "destFile.fods")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie das Cells Cloud SDK für Python, um Excel-Dateien in andere Formate, TSV in FODS, zu konvertieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `put_convert_workbook`, um den resultierenden Stream abzurufen.</li>
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
