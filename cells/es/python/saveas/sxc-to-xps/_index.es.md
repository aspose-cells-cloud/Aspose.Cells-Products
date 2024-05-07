---
title:  Guarde SXC como XPS usando Python
description: Utilizando Aspose.Cells Cloud SDK para Python para guardar el archivo en formato SXC como archivo en formato XPS.
kwords: Excel, Save SXC as XPS, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save SXC as XPS using the Cells Cloud Python library.","description": "How to save SXC as XPS using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/saveas/sxc-to-xps/","step": [{ "@type": "HowToStep","name": "How to save SXC as XPS using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/sxc-to-xps/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save SXC as XPS using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/sxc-to-xps/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save SXC as XPS using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/sxc-to-xps/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to save SXC as XPS using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/sxc-to-xps/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar SXC como XPS" h2="Biblioteca Python para guardar SXC como XPS" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Python. Esta es una solución profesional para guardar SXC como XPS y otros formatos de documentos en línea usando Python." urlsection="saveas/sxc-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo SXC como XPS en Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de SXC como XPS es una tarea compleja. Todas las transiciones de formato SXC a XPS las realiza nuestro SDK Python mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo SXC de origen. Nuestra biblioteca Python es una solución profesional para guardar SXC como archivos XPS en línea. Este SDK de nube ofrece a los desarrolladores de Python una funcionalidad potente y un resultado de XPS perfecto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Ejemplo de código para guardar SXC como XPS usando REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.sxc'    
    saveOptions = None
    newfilename = "Book1Saveas.xps"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo guardar SXC como XPS usando la biblioteca Cells Cloud Python." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Python y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Python.</li>
<li>Utilice el método `post_workbook_save_as` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Python 2.7 o más reciente</li>
<li>Python 3.10 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
