---
title:  Konvertieren Sie TSV mit Python in SQL
description:  Verwendung des Cloud SDK Aspose.Cells für Python zum Konvertieren einer TSV-Formatdatei in eine SQL-Formatdatei.
kwords: Excel, Convert TSV to SQL, REST, Python
howto: How to convert TSV to SQL using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie TSV in SQL" h2="Python Bibliothek zur Konvertierung von TSV in SQL" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Python-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von TSV in SQL und andere Dokumentformate unter Python." urlsection="conversion/tsv-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie TSV in SQL mit dem Cloud SDK Cells für Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von TSV in SQL kann eine komplexe Aufgabe sein. Unser Python SDK übernimmt alle TSV-in-SQL-Formatkonvertierungen und behält dabei den wichtigsten strukturellen und logischen Inhalt der TSV-Quelltabelle bei. Unsere Python-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von TSV- in SQL-Dateien. Dieses Cloud SDK bietet Python-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige SQL-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Codebeispiel für die Konvertierung von TSV in SQL mit Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.tsv",format="sql")
    shutil.move(file1, "destFile.sql")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Erfahren Sie, wie Sie TSV mithilfe der Cloud-Bibliothek Cells Python in SQL konvertieren." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek Python und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Python.</li>
<li>Verwenden Sie die Methode `put_convert_workbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Python 2.7 oder neuer</li>
<li>Python 3.10 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
