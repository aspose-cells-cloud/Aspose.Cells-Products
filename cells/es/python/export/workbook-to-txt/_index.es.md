---
title:  Exporte WORKBOOK a TXT desde Excel usando Cells Cloud SDK para Python
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} usando {2}.
kwords: Excel, workbook, txt, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to TXT","description": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to TXT","image": {"@type": "ImageObject"},"url": "/python/export/workbook-to-txt/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to TXT step 1", "image": {"@type": "ImageObject",},"url": "/python/export/workbook-to-txt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to TXT step 1", "image": {"@type": "ImageObject",},"url": "/python/export/workbook-to-txt/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to TXT step 1", "image": {"@type": "ImageObject",},"url": "/python/export/workbook-to-txt/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportar LIBRO DE TRABAJO a TXT desde Excel" h2="Biblioteca Python para exportar WORKBOOK a archivo TXT" p="Utilice Exportar API de Cells Cloud para exportar flujos de trabajo de objetos internos de archivos Excel en Python. Esta es una solución profesional para exportar WORKBOOK a un archivo de formato TXT desde una hoja de cálculo en línea usando Python." urlsection="export/workbook-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporte el objeto WORKBOOK a un archivo en formato TXT usando Cells Cloud SDK para Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar el objeto WORKBOOK a un archivo TXT desde el archivo Excel es una tarea compleja. Nuestro SDK Python realiza la exportación de transiciones de WORKBOOK a formato TXT manteniendo el contenido estructural y lógico principal de la hoja de cálculo de WORKBOOK de origen. Nuestra biblioteca Python es una solución profesional para exportar objetos WORKBOOK a archivos en formato TXT en línea. Este SDK de nube ofrece a los desarrolladores de Python una potente funcionalidad y una salida TXT perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código en Python usando REST API para exportar WORKBOOK a formato TXT desde una hoja de cálculo" gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"workbook","txt")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Python para exportar objetos de Excel WORKBOOK a TXT" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Llame al método post_export para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Python 2.7 o más reciente</li>
<li>Python 3.10 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
