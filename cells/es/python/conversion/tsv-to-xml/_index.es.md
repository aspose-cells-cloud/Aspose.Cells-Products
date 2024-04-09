---
title:  Convierta TSV a XML usando Python
description:  Utilizar el SDK de la nube Aspose.Cells para Python para convertir un archivo de formato TSV a un archivo de formato XML.
kwords: Excel, Convert TSV to XML, REST, Python
howto: How to convert TSV to XML using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir TSV a XML" h2="Biblioteca Python para convertir TSV a XML" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Python proyectos. Esta es una solución profesional para convertir TSV a XML y otros formatos de documentos en línea usando Python." urlsection="conversion/tsv-to-xml/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta TSV a XML usando Cells Cloud SDK para Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de TSV a XML puede ser una tarea compleja. Nuestro SDK Python maneja todas las conversiones de formato TSV a XML y al mismo tiempo conserva el contenido estructural y lógico principal de la hoja de cálculo TSV de origen. Nuestra biblioteca Python proporciona una solución profesional para convertir archivos TSV a XML en línea. Este SDK de nube brinda a los desarrolladores Python una potente funcionalidad y garantiza una salida XML de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Ejemplo de código para convertir TSV a XML usando Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.tsv",format="xml")
    shutil.move(file1, "destFile.xml")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir TSV a XML usando la biblioteca Cells Cloud Python." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Python y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Python.</li>
<li>Utilice el método `put_convert_workbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Python 2.7 o más reciente</li>
<li>Python 3.10 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
