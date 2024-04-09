---
title: Exporte IMAGEN a PNG desde Excel usando Cells Cloud SDK para Python
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} usando {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportar IMAGEN al PNG desde Excel" h2="Biblioteca Python para exportar IMAGEN al archivo PNG" p="Utilice Exportar API de Cells Cloud para exportar flujos de trabajo de objetos internos de archivos Excel en Python. Esta es una solución profesional para exportar IMAGEN a un archivo de formato PNG desde una hoja de cálculo en línea usando Python." urlsection="export/picture-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporte el objeto IMAGEN al archivo de formato PNG usando Cells Cloud SDK para Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar el objeto IMAGEN al archivo PNG desde el archivo Excel es una tarea compleja. La exportación de transiciones de IMAGEN a formato PNG se realiza mediante nuestro SDK Python mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo de IMAGEN de origen. Nuestra biblioteca Python es una solución profesional para exportar objetos de IMAGEN a archivos de formato PNG en línea. Este SDK de nube ofrece a los desarrolladores de Python una funcionalidad potente y un resultado de PNG perfecto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código en Python usando REST API para exportar IMAGEN al formato PNG desde una hoja de cálculo" gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"picture","png")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Python para exportar objetos de Excel IMAGEN a PNG" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Llame al método post_export para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Python 2.7 o más reciente</li>
<li>Python 3.10 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
