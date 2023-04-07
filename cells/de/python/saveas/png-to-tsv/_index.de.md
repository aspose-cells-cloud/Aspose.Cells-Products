﻿---
title: Speichern Sie PNG als TSV API für Python
description:  Cloud-APIs und SDKs für Microsoft Excel und OpenOffice Calc. Konvertieren Sie die Tabelle in ein anderes Dateiformat.
url: /de/python/saveas/png-to-tsv/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API um PNG als TSV zu speichern" h2="Python-Bibliothek zum Speichern von PNG als TSV" p="Verwenden Sie Cells SaveAs REST API, um benutzerdefinierte Tabellenkalkulations-Workflows in Python zu erstellen. Dies ist eine professionelle Lösung, um PNG als TSV und andere Dokumentformate online mit Python zu speichern." urlsection="saveas/png-to-tsv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Speichern Sie eine PNG-Datei als TSV in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten von PNG als TSV ist eine komplexe Aufgabe. Alle Formatübergänge von PNG zu TSV werden von unserem Python SDK durchgeführt, während der strukturelle und logische Hauptinhalt der Quelltabelle PNG beibehalten wird. Unsere Python-Bibliothek ist eine professionelle Lösung, um PNG als TSV-Dateien online zu speichern. Dieses Cloud-SDK bietet Python-Entwicklern leistungsstarke Funktionen und perfekte TSV-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in Python mit REST API zum Speichern von PNG im TSV-Format" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.png'    
    saveOptions = None
    newfilename = "Book1Saveas.tsv"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Python API, um PNG als TSV zu speichern" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um kostenlose API Kontingent- und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und API-Version</li>
<li>Zellen anrufen_speichern_als_Post_dokumentieren_speichern_als Methode, um den resultierenden Stream zu erhalten</li>
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