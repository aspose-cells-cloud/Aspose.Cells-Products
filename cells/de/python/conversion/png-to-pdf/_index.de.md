---
title:  Konvertieren Sie PNG mit Python in PDF
description:  Verwendung des Aspose.Cells Cloud SDK für Python zum Konvertieren einer Datei im Format PNG in eine Datei im Format PDF.
kwords: Excel, Convert PNG to PDF, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert PNG to PDF using the Cells Cloud Python library.","description": "How to convert PNG to PDF using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/conversion/png-to-pdf/","step": [{ "@type": "HowToStep","name": "How to convert PNG to PDF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/png-to-pdf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert PNG to PDF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/png-to-pdf/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert PNG to PDF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/png-to-pdf/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to convert PNG to PDF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/png-to-pdf/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie PNG in PDF" h2="Python-Bibliothek zum Konvertieren von PNG in PDF" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Python-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Konvertieren von PNG in PDF und andere Dokumentformate online mit Python." urlsection="conversion/png-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie PNG in PDF mit dem Cloud SDK Cells für Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von PNG nach PDF kann eine komplexe Aufgabe sein. Unser Python SDK bewältigt alle Formatkonvertierungen von PNG nach PDF und bewahrt dabei den strukturellen und logischen Hauptinhalt der Quelltabelle PNG. Unsere Python-Bibliothek bietet eine professionelle Lösung zum Online-Konvertieren von Dateien von PNG nach PDF. Dieses Cloud SDK bietet Python-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige PDF-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Codebeispiel zur Konvertierung von PNG in PDF mit Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.png",format="pdf")
    shutil.move(file1, "destFile.pdf")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So konvertieren Sie PNG in PDF mithilfe der Cells Cloud Python-Bibliothek." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek Python und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Python.</li>
<li>Verwenden Sie die Methode `put_convert_workbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Python 2.7 oder neuer</li>
<li>Python 3.10 oder neuer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
