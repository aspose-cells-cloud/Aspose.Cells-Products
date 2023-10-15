---
title:  Convierta JSON a CSV usando Python
description:  Utilizar el SDK de la nube Aspose.Cells para Python para convertir un archivo de formato JSON a un archivo de formato CSV.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir JSON a CSV" h2="Biblioteca Python para convertir JSON a CSV" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Python proyectos. Esta es una solución profesional para convertir JSON a CSV y otros formatos de documentos en línea usando Python." urlsection="conversion/json-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta JSON a CSV usando Cells Cloud SDK para Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de JSON a CSV puede ser una tarea compleja. Nuestro SDK Python maneja todas las conversiones de formato JSON a CSV y al mismo tiempo conserva el contenido estructural y lógico principal de la hoja de cálculo JSON de origen. Nuestra biblioteca Python proporciona una solución profesional para convertir archivos JSON a CSV en línea. Este SDK de nube brinda a los desarrolladores de Python una potente funcionalidad y garantiza una salida CSV de alta calidad.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Ejemplo de código para convertir JSON a CSV usando Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.json",format="csv")
    shutil.move(file1, "destFile.csv")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Python para convertir archivos Excel a otros formatos JSON a CSV" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `put_convert_workbook` para recuperar la secuencia resultante.</li>
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
