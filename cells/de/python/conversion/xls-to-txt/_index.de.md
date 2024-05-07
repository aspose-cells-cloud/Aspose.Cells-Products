---
title:  Konvertieren Sie XLS mit Python in TXT
description:  Verwendung des Aspose.Cells Cloud SDK für Python zum Konvertieren einer Datei im XLS-Format in eine Datei im TXT-Format.
kwords: Excel, Convert XLS to TXT, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLS to TXT using the Cells Cloud Python library.","description": "How to convert XLS to TXT using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/conversion/xls-to-txt/","step": [{ "@type": "HowToStep","name": "How to convert XLS to TXT using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/xls-to-txt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLS to TXT using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/xls-to-txt/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLS to TXT using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/xls-to-txt/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to convert XLS to TXT using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/xls-to-txt/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie XLS in TXT" h2="Python Bibliothek zum Konvertieren von XLS in TXT" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Python-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XLS in TXT und andere Dokumentformate unter Python." urlsection="conversion/xls-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie XLS in TXT mit dem Cloud SDK Cells für Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLS in TXT kann eine komplexe Aufgabe sein. Unser Python SDK übernimmt alle Konvertierungen des XLS- in das TXT-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der XLS-Quelltabelle bei. Unsere Python-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von XLS- in TXT-Dateien. Dieses Cloud SDK bietet Python-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige TXT-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Codebeispiel für die Konvertierung von XLS in TXT mit Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xls",format="txt")
    shutil.move(file1, "destFile.txt")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So konvertieren Sie XLS in TXT mit der Cells Cloud Python-Bibliothek." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek Python und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Python.</li>
<li>Verwenden Sie die Methode `put_convert_workbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Python 2.7 oder neuer</li>
<li>Python 3.10 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
