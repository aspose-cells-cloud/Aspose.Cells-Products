---
title:  Speichern Sie XLSX unter PDF mit Python
description:  Verwendung des Cloud SDK Aspose.Cells für Python zum Speichern der Datei im XLSX-Format als Datei im Format PDF.
kwords: Excel, Save XLSX as PDF, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLSX as PDF using the Cells Cloud Python library.","description": "How to save XLSX as PDF using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/saveas/xlsx-to-pdf/","step": [{ "@type": "HowToStep","name": "How to save XLSX as PDF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xlsx-to-pdf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLSX as PDF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xlsx-to-pdf/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLSX as PDF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xlsx-to-pdf/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to save XLSX as PDF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xlsx-to-pdf/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="XLSX speichern unter PDF" h2="Python-Bibliothek zum Speichern von XLSX als PDF" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Python zu erstellen. Dies ist eine professionelle Lösung, um XLSX als PDF und andere Dokumentformate online unter Python zu speichern." urlsection="saveas/xlsx-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine XLSX-Datei als PDF in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus XLSX als PDF ist eine komplexe Aufgabe. Alle Formatübergänge von XLSX in das Format PDF werden von unserem SDK Python durchgeführt, wobei der strukturelle und logische Hauptinhalt der XLSX-Quelltabelle erhalten bleibt. Unsere Python-Bibliothek ist eine professionelle Lösung, um XLSX als PDF-Dateien online zu speichern. Dieses Cloud SDK bietet Python Entwicklern leistungsstarke Funktionalität und eine perfekte PDF Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Codebeispiel zum Speichern von XLSX als PDF mit REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlsx'    
    saveOptions = None
    newfilename = "Book1Saveas.pdf"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So speichern Sie XLSX als PDF mithilfe der Cells Cloud Python-Bibliothek." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek Python und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Python.</li>
<li>Verwenden Sie die Methode `post_workbook_save_as`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Python 2.7 oder neuer</li>
<li>Python 3.10 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
