---
title:  Convierta TXT a PPTX usando Python
description:  Utilizar el SDK de la nube Aspose.Cells para Python para convertir un archivo de formato TXT a un archivo de formato PPTX.
kwords: Excel, Convert TXT to PPTX, REST, Python
howto: How to convert TXT to PPTX using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir TXT a PPTX" h2="Biblioteca Python para convertir TXT a PPTX" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Python proyectos. Esta es una solución profesional para convertir TXT a PPTX y otros formatos de documentos en línea usando Python." urlsection="conversion/txt-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta TXT a PPTX usando Cells Cloud SDK para Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de TXT a PPTX puede ser una tarea compleja. Nuestro SDK Python maneja todas las conversiones de formato TXT a PPTX al tiempo que conserva el contenido estructural y lógico principal de la hoja de cálculo TXT de origen. Nuestra biblioteca Python proporciona una solución profesional para convertir archivos TXT a PPTX en línea. Este SDK de nube brinda a los desarrolladores Python una potente funcionalidad y garantiza una salida PPTX de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Ejemplo de código para convertir TXT a PPTX usando Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.txt",format="pptx")
    shutil.move(file1, "destFile.pptx")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir TXT a PPTX usando la biblioteca Cells Cloud Python." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Python y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Python.</li>
<li>Utilice el método `put_convert_workbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Python 2.7 o más reciente</li>
<li>Python 3.10 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
