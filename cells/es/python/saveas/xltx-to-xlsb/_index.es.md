---
title:  Guarde XLTX como XLSB usando Python
description:  Utilizando Aspose.Cells Cloud SDK para Python para guardar el archivo en formato XLTX como archivo en formato XLSB.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Guardar XLTX como XLSB" h2="Biblioteca Python para guardar XLTX como XLSB" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Python. Esta es una solución profesional para guardar XLTX como XLSB y otros formatos de documentos en línea usando Python." urlsection="saveas/xltx-to-xlsb/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo XLTX como XLSB en Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLTX como XLSB es una tarea compleja. Todas las transiciones de formato XLTX a XLSB se realizan mediante nuestro SDK Python manteniendo el contenido estructural y lógico principal de la hoja de cálculo XLTX de origen. Nuestra biblioteca Python es una solución profesional para guardar XLTX como archivos XLSB en línea. Este SDK de nube ofrece a los desarrolladores de Python una potente funcionalidad y una salida XLSB perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Ejemplo de código para guardar XLTX como XLSB usando REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xltx'    
    saveOptions = None
    newfilename = "Book1Saveas.xlsb"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Python para guardar archivos Excel como otros formatos XLTX como XLSB" >}}
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
