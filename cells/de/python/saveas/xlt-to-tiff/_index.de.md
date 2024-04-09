---
title:  Speichern Sie XLT unter TIFF mit Python
description:  Verwendung des Aspose.Cells Cloud SDK für Python zum Speichern der XLT-Formatdatei als TIFF-Formatdatei.
kwords: Excel, Save XLT as TIFF, REST, Python
howto: How to save XLT as TIFF using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie XLT unter TIFF" h2="Python-Bibliothek zum Speichern von XLT als TIFF" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Python zu erstellen. Dies ist eine professionelle Lösung, um XLT als TIFF und andere Dokumentformate online unter Python zu speichern." urlsection="saveas/xlt-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine XLT-Datei unter TIFF in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus XLT als TIFF ist eine komplexe Aufgabe. Alle XLT-Formatübergänge in das TIFF-Format werden von unserem Python-SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der XLT-Quelltabelle erhalten bleibt. Unsere Python-Bibliothek ist eine professionelle Lösung, um XLT als TIFF-Dateien online zu speichern. Dieses Cloud SDK bietet Python Entwicklern leistungsstarke Funktionalität und eine perfekte TIFF Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Codebeispiel zum Speichern von XLT als TIFF mit REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlt'    
    saveOptions = None
    newfilename = "Book1Saveas.tiff"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Erfahren Sie, wie Sie XLT mit der Cells Cloud Python-Bibliothek als TIFF speichern." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek Python und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Python.</li>
<li>Verwenden Sie die Methode `post_workbook_save_as`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Python 2.7 oder neuer</li>
<li>Python 3.10 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
