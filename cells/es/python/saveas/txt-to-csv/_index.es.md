---
title: Guarde TXT como CSV usando Python
description:  Utilizando Aspose.Cells Cloud SDK para Python para guardar el archivo en formato TXT como archivo en formato CSV.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Guardar TXT como CSV" h2="Biblioteca Python para guardar TXT como CSV" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Python. Esta es una solución profesional para guardar TXT como CSV y otros formatos de documentos en línea usando Python." urlsection="saveas/txt-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo TXT como CSV en Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de TXT como CSV es una tarea compleja. Todas las transiciones de formato TXT a CSV se realizan mediante nuestro SDK Python mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo TXT de origen. Nuestra biblioteca Python es una solución profesional para guardar TXT como archivos CSV en línea. Este SDK de nube ofrece a los desarrolladores de Python una potente funcionalidad y una salida CSV perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Ejemplo de código para guardar TXT como CSV usando REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.txt'    
    saveOptions = None
    newfilename = "Book1Saveas.csv"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Python para guardar archivos Excel en otros formatos TXT como CSV" >}}
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
