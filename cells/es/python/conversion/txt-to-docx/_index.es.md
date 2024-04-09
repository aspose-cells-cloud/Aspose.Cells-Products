---
title: Convierta TXT a DOCX usando Python
description:  Utilizar el SDK de la nube Aspose.Cells para Python para convertir un archivo en formato TXT a un archivo en formato DOCX.
kwords: Excel, Convert TXT to DOCX, REST, Python
howto: How to convert TXT to DOCX using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir TXT a DOCX" h2="Biblioteca Python para convertir TXT a DOCX" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Python proyectos. Esta es una solución profesional para convertir TXT a DOCX y otros formatos de documentos en línea usando Python." urlsection="conversion/txt-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta TXT a DOCX usando Cells Cloud SDK para Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de TXT a DOCX puede ser una tarea compleja. Nuestro SDK Python maneja todas las conversiones de formato TXT a DOCX al tiempo que conserva el contenido estructural y lógico principal de la hoja de cálculo TXT de origen. Nuestra biblioteca Python proporciona una solución profesional para convertir archivos TXT a DOCX en línea. Este SDK de nube brinda a los desarrolladores Python una potente funcionalidad y garantiza una salida DOCX de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Ejemplo de código para convertir TXT a DOCX usando Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.txt",format="docx")
    shutil.move(file1, "destFile.docx")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir TXT a DOCX usando la biblioteca Cells Cloud Python." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Python y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Python.</li>
<li>Utilice el método `put_convert_workbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Python 2.7 o más reciente</li>
<li>Python 3.10 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
