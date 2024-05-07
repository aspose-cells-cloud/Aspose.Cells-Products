---
title:  Exportera LISTOBJECT till JPG från Excel med Cells Cloud SDK för Python
description:  Aspose.Cells Cloud REST API stöder export av filer från {0} till {1}-format med {2}.
kwords: Excel, listobject, jpg, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to JPG","description": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to JPG","image": {"@type": "ImageObject"},"url": "/python/export/listobject-to-jpg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to JPG step 1", "image": {"@type": "ImageObject",},"url": "/python/export/listobject-to-jpg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to JPG step 1", "image": {"@type": "ImageObject",},"url": "/python/export/listobject-to-jpg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel LISTOBJECT to JPG step 1", "image": {"@type": "ImageObject",},"url": "/python/export/listobject-to-jpg/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportera LISTOBJEKT till JPG från Excel" h2="Python bibliotek för export av LISTOBJECT till JPG-fil" p="Använd Export API av Cells Cloud för att exportera Excel fil interna objekt arbetsflöden i Python. Detta är en professionell lösning för att exportera LISTOBJECT till JPG-format fil från kalkylblad online med Python." urlsection="export/listobject-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportera LISTOBJECT-objekt till JPG-formatfil med Cells Cloud SDK för Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportera LISTOBJECT-objekt till JPG-fil från Excel-filen är en komplex uppgift. Export av övergångar av LISTOBJECT till JPG-format utförs av vår Python SDK samtidigt som källbladets LISTOBJECT-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Python-bibliotek är en professionell lösning för att exportera LISTOBJECT-objekt till JPG-formatfiler online. Denna Cloud SDK ger Python utvecklare kraftfull funktionalitet och perfekt JPG-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Kodexempel i Python med REST API för att exportera LISTOBJECT till JPG-format från kalkylark" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import base64
    from asposecellscloud.apis.light_cells_api import LightCellsApi
    cells_api = LightCellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    files ={ 
        "myDocument.xlsx" :  "c:/myDocument.xlsx",
        "Book1.xlsx" :  "c:/Book1.xlsx" 
        }
    result = cells_api.post_export(files ,"listobject","jpg")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för Python för att exportera objekt från Excel LISTOBJECT till JPG" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Anrop post_export-metoden för att hämta den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Python 2.7 eller nyare</li>
<li>Python 3.10 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
