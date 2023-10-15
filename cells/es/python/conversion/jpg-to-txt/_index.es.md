---
title:  Convierta JPG a TXT usando Python
description:  Utilizar el SDK de la nube Aspose.Cells para Python para convertir un archivo de formato JPG a un archivo de formato TXT.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir JPG a TXT" h2="Biblioteca Python para convertir JPG a TXT" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Python proyectos. Esta es una solución profesional para convertir JPG a TXT y otros formatos de documentos en línea usando Python." urlsection="conversion/jpg-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta JPG a TXT usando Cells Cloud SDK para Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de JPG a TXT puede ser una tarea compleja. Nuestro SDK Python maneja todas las conversiones de formato JPG a TXT preservando al mismo tiempo el contenido estructural y lógico principal de la hoja de cálculo JPG de origen. Nuestra biblioteca Python proporciona una solución profesional para convertir archivos JPG a TXT en línea. Este SDK de nube brinda a los desarrolladores Python una potente funcionalidad y garantiza una salida TXT de alta calidad.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Ejemplo de código para convertir JPG a TXT usando Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.jpg",format="txt")
    shutil.move(file1, "destFile.txt")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Python para convertir archivos Excel a otros formatos JPG a TXT" >}}
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
