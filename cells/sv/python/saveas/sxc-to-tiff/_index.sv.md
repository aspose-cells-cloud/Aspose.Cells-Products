---
title:  Spara SXC som TIFF med Python
description: Använder Aspose.Cells Cloud SDK för Python för att spara fil i SXC-format som fil i TIFF-format.
kwords: Excel, Save SXC as TIFF, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save SXC as TIFF using the Cells Cloud Python library.","description": "How to save SXC as TIFF using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/saveas/sxc-to-tiff/","step": [{ "@type": "HowToStep","name": "How to save SXC as TIFF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/sxc-to-tiff/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save SXC as TIFF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/sxc-to-tiff/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save SXC as TIFF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/sxc-to-tiff/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to save SXC as TIFF using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/sxc-to-tiff/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Spara SXC som TIFF" h2="Python bibliotek för att spara SXC som TIFF" p="Använd SaveAs API av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Python. Detta är en professionell lösning för att spara SXC som TIFF och andra dokumentformat online med Python." urlsection="saveas/sxc-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Spara en SXC-fil som TIFF i Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från SXC som TIFF är en komplex uppgift. Alla SXC- till TIFF-formatövergångar utförs av vår Python SDK samtidigt som käll-SXC-kalkylbladets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Python-bibliotek är en professionell lösning för att spara SXC som TIFF-filer online. Denna Cloud SDK ger Python-utvecklare kraftfull funktionalitet och perfekt TIFF-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Kod Exempel för att spara SXC som TIFF med REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.sxc'    
    saveOptions = None
    newfilename = "Book1Saveas.tiff"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man sparar SXC som TIFF med Cells Cloud Python-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Python-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Python.</li>
<li>Använd metoden `post_workbook_save_as` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Python 2.7 eller nyare</li>
<li>Python 3.10 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
