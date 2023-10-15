---
title:  Speichern Sie GIF als TXT mit Python
description:  Verwendung von Aspose.Cells Cloud SDK für Python zum Speichern von GIF-Formatdateien als TXT-Formatdateien.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="GIF als TXT speichern" h2="Python Bibliothek zum Speichern von GIF als TXT" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Python zu erstellen. Dies ist eine professionelle Lösung, um GIF als TXT und andere Dokumentformate online mit Python zu speichern." urlsection="saveas/gif-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Speichern Sie eine GIF-Datei als TXT unter Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von GIF-Dateiformaten als TXT ist eine komplexe Aufgabe. Alle Übergänge vom GIF- zum TXT-Format werden von unserem SDK Python durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quell-GIF-Tabelle erhalten bleibt. Unsere Python-Bibliothek ist eine professionelle Lösung, um GIF als TXT-Dateien online zu speichern. Dieses Cloud SDK bietet Python Entwicklern leistungsstarke Funktionalität und perfekte TXT-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Codebeispiel zum Speichern von GIF als TXT mit REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.gif'    
    saveOptions = None
    newfilename = "Book1Saveas.txt"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie das Cells Cloud SDK für Python, um Excel-Dateien in anderen Formaten wie GIF und TXT zu speichern" >}}
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
