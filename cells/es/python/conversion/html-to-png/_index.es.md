---
title:  Convierta HTML a PNG usando Python
description:  Utilizar el SDK de la nube Aspose.Cells para Python para convertir un archivo de formato HTML a un archivo de formato PNG.
kwords: Excel, Convert HTML to PNG, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert HTML to PNG using the Cells Cloud Python library.","description": "How to convert HTML to PNG using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/conversion/html-to-png/","step": [{ "@type": "HowToStep","name": "How to convert HTML to PNG using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/html-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert HTML to PNG using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/html-to-png/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert HTML to PNG using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/html-to-png/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to convert HTML to PNG using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/html-to-png/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir HTML a PNG" h2="Biblioteca Python para convertir HTML a PNG" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Python proyectos. Esta es una solución profesional para convertir HTML a PNG y otros formatos de documentos en línea usando Python." urlsection="conversion/html-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta HTML a PNG usando Cells Cloud SDK para Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de HTML a PNG puede ser una tarea compleja. Nuestro SDK Python maneja todas las conversiones de formato HTML a PNG y al mismo tiempo conserva el contenido estructural y lógico principal de la hoja de cálculo de origen HTML. Nuestra biblioteca Python proporciona una solución profesional para convertir archivos HTML a PNG en línea. Este SDK de nube brinda a los desarrolladores de Python una potente funcionalidad y garantiza resultados de PNG de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Ejemplo de código para convertir HTML a PNG usando Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.html",format="png")
    shutil.move(file1, "destFile.png")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo convertir HTML a PNG usando la biblioteca Cells Cloud Python." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Python y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Python.</li>
<li>Utilice el método `put_convert_workbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Python 2.7 o más reciente</li>
<li>Python 3.10 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
