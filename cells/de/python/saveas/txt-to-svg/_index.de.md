---
title:  Speichern Sie TXT unter SVG mit Python
description:  Verwendung des Aspose.Cells Cloud SDK für Python zum Speichern der TXT-Formatdatei als SVG-Formatdatei.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Speichern Sie TXT unter SVG" h2="Python-Bibliothek zum Speichern von TXT als SVG" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Python zu erstellen. Dies ist eine professionelle Lösung, um TXT als SVG und andere Dokumentformate online unter Python zu speichern." urlsection="saveas/txt-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Speichern Sie eine TXT-Datei unter SVG in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus TXT als SVG ist eine komplexe Aufgabe. Alle TXT-Formatübergänge in das SVG-Format werden von unserem Python-SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der TXT-Quelltabelle erhalten bleibt. Unsere Python-Bibliothek ist eine professionelle Lösung, um TXT als SVG-Dateien online zu speichern. Dieses Cloud SDK bietet Python Entwicklern leistungsstarke Funktionalität und eine perfekte SVG Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Codebeispiel zum Speichern von TXT als SVG mit REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.txt'    
    saveOptions = None
    newfilename = "Book1Saveas.svg"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für Python, um Excel-Dateien in anderen TXT-Formaten als SVG zu speichern" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `post_workbook_save_as`, um den resultierenden Stream abzurufen.</li>
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
