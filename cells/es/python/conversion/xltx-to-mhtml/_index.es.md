﻿---
title:  XLTX a MHTML Convertir API para Python
description:  Usando Aspose.Cells Cloud SDK para Python para convertir un archivo de formato XLTX a un archivo de formato MHTML.
url: /es/python/conversion/xltx-to-mhtml/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API para convertir XLTX a MHTML" h2="Python biblioteca para convertir XLTX a MHTML" p="Use Cells Conversión REST API para crear flujos de trabajo de hojas de cálculo personalizados en Python. Esta es una solución profesional para convertir XLTX a MHTML y otros formatos de documentos en línea usando Python." urlsection="conversion/xltx-to-mhtml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta un archivo XLTX a MHTML en Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de XLTX a MHTML es una tarea compleja. Todas las transiciones de formato XLTX a MHTML se realizan mediante nuestro SDK Python mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLTX de origen. Nuestra biblioteca Python es una solución profesional para convertir archivos XLTX a MHTML en línea. Este SDK de Cloud brinda a los desarrolladores de Python una funcionalidad poderosa y una salida MHTML perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Python usando REST API para convertir XLTX a formato MHTML" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xltx",format="mhtml")
    shutil.move(file1, "destFile.mhtml")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Python API para convertir XLTX a MHTML" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llamar a celdas_libro de trabajo_poner_convertir_método del libro de trabajo para obtener el flujo resultante</li>
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