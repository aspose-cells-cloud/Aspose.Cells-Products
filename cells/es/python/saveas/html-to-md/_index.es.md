---
title:  Guarde HTML como MD usando Python
description:  Utilizando Aspose.Cells Cloud SDK para Python para guardar el archivo de formato HTML como archivo de formato MD.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Guardar HTML como MD" h2="Biblioteca Python para guardar HTML como MD" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Python. Esta es una solución profesional para guardar HTML como MD y otros formatos de documentos en línea usando Python." urlsection="saveas/html-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo HTML como MD en Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de HTML como MD es una tarea compleja. Todas las transiciones de formato HTML a MD las realiza nuestro SDK Python manteniendo el contenido estructural y lógico principal de la hoja de cálculo de origen HTML. Nuestra biblioteca Python es una solución profesional para guardar HTML como archivos MD en línea. Este SDK de nube ofrece a los desarrolladores de Python una funcionalidad potente y una salida MD perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Ejemplo de código para guardar HTML como MD usando REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.html'    
    saveOptions = None
    newfilename = "Book1Saveas.md"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Python para guardar archivos Excel en otros formatos HTML como MD" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `post_workbook_save_as` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Python 2.7 o más reciente</li>
<li>Python 3.10 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
