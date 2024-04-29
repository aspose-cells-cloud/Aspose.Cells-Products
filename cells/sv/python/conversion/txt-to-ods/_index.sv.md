---
title:  Konvertera TXT till ODS med Python
description:  Använda Aspose.Cells Cloud SDK för Python för att konvertera en fil i TXT-format till en fil i ODS-format.
kwords: Excel, Convert TXT to ODS, REST, Python
howto: "{"@context": "https://schema.org","@type": "HowTo","name": "How to convert TXT to ODS using the Cells Cloud Python library.","description": "How to convert TXT to ODS using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/conversion/txt-to-ods/","step": [{ "@type": "HowToStep","name": "How to convert TXT to ODS using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/txt-to-ods/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert TXT to ODS using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/txt-to-ods/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert TXT to ODS using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/txt-to-ods/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to convert TXT to ODS using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/txt-to-ods/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}"
fqa: "{"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}"
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera TXT till ODS" h2="Python bibliotek för att konvertera TXT till ODS" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Python projekt. Detta är en professionell lösning för att konvertera TXT till ODS och andra dokumentformat online med Python." urlsection="conversion/txt-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera TXT till ODS med Cells Cloud SDK för Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från TXT till ODS kan vara en komplex uppgift. Vår Python SDK hanterar alla konverteringar av TXT till ODS-format samtidigt som det huvudsakliga strukturella och logiska innehållet i källarket för TXT bevaras. Vårt Python-bibliotek tillhandahåller en professionell lösning för att konvertera TXT till ODS-filer online. Denna Cloud SDK ger Python utvecklare kraftfull funktionalitet och säkerställer högkvalitativa ODS-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Kodexempel för att konvertera TXT till ODS med Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.txt",format="ods")
    shutil.move(file1, "destFile.ods")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man konverterar TXT till ODS med hjälp av Cells Cloud Python-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Python-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Python.</li>
<li>Använd metoden `put_convert_workbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Python 2.7 eller nyare</li>
<li>Python 3.10 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
