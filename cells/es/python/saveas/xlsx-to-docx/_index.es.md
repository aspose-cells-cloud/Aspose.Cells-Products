﻿---
title:  Guarde XLSX como DOCX API para Python
description:  Usando Aspose.Cells Cloud SDK para Python para guardar el archivo de formato XLSX como archivo de formato DOCX.
url: /es/python/saveas/xlsx-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API para guardar XLSX como DOCX" h2="Python biblioteca para guardar XLSX como DOCX" p="Use Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Python. Esta es una solución profesional para guardar XLSX como DOCX y otros formatos de documentos en línea usando Python." urlsection="saveas/xlsx-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo XLSX como DOCX en Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLSX como DOCX es una tarea compleja. Todas las transiciones de formato XLSX a DOCX se realizan mediante nuestro SDK Python mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLSX de origen. Nuestra biblioteca Python es una solución profesional para guardar XLSX como archivos DOCX en línea. Este SDK de la nube brinda a los desarrolladores de Python una funcionalidad poderosa y una salida DOCX perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Python usando REST API para guardar XLSX como formato DOCX" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlsx'    
    saveOptions = None
    newfilename = "Book1Saveas.docx"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Python API para guardar XLSX como DOCX" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llamar a celdas_ahorrar_como_correo_documento_ahorrar_como método para obtener el flujo resultante</li>
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