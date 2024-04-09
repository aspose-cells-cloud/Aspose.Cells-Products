---
title:  Guarde NÚMEROS como ODS usando Python
description:  Utilizando Aspose.Cells Cloud SDK para Python para guardar el archivo en formato NUMBERS como archivo en formato ODS.
kwords: Excel, Save NUMBERS as ODS, REST, Python
howto: How to save NUMBERS as ODS using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar NÚMEROS como ODS" h2="Biblioteca Python para guardar NÚMEROS como ODS" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Python. Esta es una solución profesional para guardar NÚMEROS como ODS y otros formatos de documentos en línea usando Python." urlsection="saveas/numbers-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo NUMBERS como ODS en Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de NUMBERS como ODS es una tarea compleja. Todas las transiciones de formato de NUMBERS a ODS se realizan mediante nuestro SDK Python mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo de NUMBERS de origen. Nuestra biblioteca Python es una solución profesional para guardar NÚMEROS como archivos ODS en línea. Este SDK de nube ofrece a los desarrolladores de Python una potente funcionalidad y una salida ODS perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Ejemplo de código para guardar NÚMEROS como ODS usando REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.numbers'    
    saveOptions = None
    newfilename = "Book1Saveas.ods"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo guardar NÚMEROS como ODS usando la biblioteca Cells Cloud Python." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Python y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Python.</li>
<li>Utilice el método `post_workbook_save_as` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Python 2.7 o más reciente</li>
<li>Python 3.10 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
