---
title:  Convierta ODS a SXC usando Python
description:  Utilizar el SDK de la nube Aspose.Cells para Python para convertir un archivo en formato ODS a un archivo en formato SXC.
kwords: Excel, Convert ODS to SXC, REST, Python
howto: How to convert ODS to SXC using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir ODS a SXC" h2="Biblioteca Python para convertir ODS a SXC" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Python proyectos. Esta es una solución profesional para convertir ODS a SXC y otros formatos de documentos en línea usando Python." urlsection="conversion/ods-to-sxc/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta ODS a SXC usando Cells Cloud SDK para Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de ODS a SXC puede ser una tarea compleja. Nuestro SDK Python maneja todas las conversiones de formato ODS a SXC al tiempo que conserva el contenido estructural y lógico principal de la hoja de cálculo ODS de origen. Nuestra biblioteca Python proporciona una solución profesional para convertir archivos ODS a SXC en línea. Este SDK de nube brinda a los desarrolladores de Python una potente funcionalidad y garantiza una salida SXC de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Ejemplo de código para convertir ODS a SXC usando Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.ods",format="sxc")
    shutil.move(file1, "destFile.sxc")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir ODS a SXC usando la biblioteca Cells Cloud Python." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Python y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Python.</li>
<li>Utilice el método `put_convert_workbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Python 2.7 o más reciente</li>
<li>Python 3.10 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
