﻿---
title:  Exporte el LIBRO DE TRABAJO a TIFF desde la hoja de cálculo usando Python API
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} mediante {2}.
url: /es/python/export/workbook-to-tiff/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API para exportar el LIBRO DE TRABAJO al archivo TIFF" h2="Python biblioteca para exportar el LIBRO DE TRABAJO al archivo TIFF" p="Use Cells Export REST API para exportar flujos de trabajo de objetos internos de hoja de cálculo en Python. Esta es una solución profesional para exportar WORKBOOK a un archivo de formato TIFF desde una hoja de cálculo en línea usando Python." urlsection="export/workbook-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exporte el objeto WORKBOOK al archivo de formato TIFF en Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar el objeto WORKBOOK al archivo TIFF desde la hoja de cálculo es una tarea compleja. Exportar WORKBOOK a transiciones de formato TIFF se realiza mediante nuestro SDK Python mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo WORKBOOK de origen. Nuestra biblioteca Python es una solución profesional para exportar objetos de WORKBOOK a archivos de formato TIFF en línea. Este SDK de Cloud ofrece a los desarrolladores de Python una potente funcionalidad y un resultado TIFF perfecto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Python usando REST API para exportar el LIBRO DE TRABAJO al formato TIFF desde la hoja de cálculo" gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"workbook","tiff")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Python API para exportar WORKBOOK a TIFF" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método post_export para obtener el flujo resultante</li>
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