---
title:  Esporta SHAPE in PNG da Excel utilizzando Cells Cloud SDK per Python
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
kwords: Excel, shape, png, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Python to export objects from Excel SHAPE to PNG","description": "How to use Cells Cloud SDK for Python to export objects from Excel SHAPE to PNG","image": {"@type": "ImageObject"},"url": "/python/export/shape-to-png/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel SHAPE to PNG step 1", "image": {"@type": "ImageObject",},"url": "/python/export/shape-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel SHAPE to PNG step 1", "image": {"@type": "ImageObject",},"url": "/python/export/shape-to-png/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel SHAPE to PNG step 1", "image": {"@type": "ImageObject",},"url": "/python/export/shape-to-png/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Esporta SHAPE a PNG da Excel" h2="Libreria Python per esportare SHAPE nel file PNG" p="Utilizza Esporta API di Cells Cloud per esportare i flussi di lavoro degli oggetti interni del file Excel in Python. Questa è una soluzione professionale per esportare SHAPE nel file in formato PNG dal foglio di calcolo online utilizzando Python." urlsection="export/shape-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Esporta l\'oggetto SHAPE nel file in formato PNG utilizzando Cells Cloud SDK per Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto SHAPE nel file PNG dal file Excel è un'attività complessa. L'esportazione di SHAPE nelle transizioni del formato PNG viene eseguita dal nostro SDK Python mantenendo il contenuto strutturale e logico principale del foglio di calcolo SHAPE di origine. La nostra libreria Python è una soluzione professionale per esportare oggetti SHAPE in file in formato PNG online. Questo Cloud SDK offre agli sviluppatori Python funzionalità potenti e un output PNG perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice in Python utilizzando REST API per esportare SHAPE nel formato PNG dal foglio di calcolo" gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"shape","png")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Python per esportare oggetti da Excel SHAPE a PNG" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Chiama il metodo post_export per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Python 2.7 o successiva</li>
<li>Python 3.10 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
