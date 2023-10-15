---
title:  Konvertieren Sie ODS mit Python in PPTX
description:  Verwendung des Aspose.Cells Cloud SDK für Python zum Konvertieren einer Datei im ODS-Format in eine Datei im PPTX-Format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertieren Sie ODS in PPTX" h2="Python Bibliothek zur Konvertierung von ODS in PPTX" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Python-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von ODS in PPTX und andere Dokumentformate unter Python." urlsection="conversion/ods-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie ODS in PPTX mit dem Cloud SDK Cells für Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von ODS in PPTX kann eine komplexe Aufgabe sein. Unser Python SDK übernimmt alle Konvertierungen von ODS in das PPTX-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der Quell-ODS-Tabelle bei. Unsere Python-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von ODS- in PPTX-Dateien. Dieses Cloud SDK bietet Python-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige PPTX-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Codebeispiel für die Konvertierung von ODS in PPTX mit Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.ods",format="pptx")
    shutil.move(file1, "destFile.pptx")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie das Cells Cloud SDK für Python, um Excel-Dateien in andere Formate, ODS in PPTX, zu konvertieren" >}}
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
