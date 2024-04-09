---
title:  Convierta GIF a PPTX usando NodeJS
description:  Utilizar el SDK de la nube Aspose.Cells para NodeJS para convertir un archivo de formato GIF a un archivo de formato PPTX.
kwords: Excel, Convert GIF to PPTX, REST, NodeJS
howto: How to convert GIF to PPTX using Aspose.Cells Cloud NodeJS library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir GIF a PPTX" h2="Biblioteca NodeJS para convertir GIF a PPTX" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en proyectos NodeJS. Esta es una solución profesional para convertir GIF a PPTX y otros formatos de documentos en línea usando NodeJS." urlsection="conversion/gif-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta GIF a PPTX usando Cells Cloud SDK para NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de GIF a PPTX puede ser una tarea compleja. Nuestro SDK de NodeJS maneja todas las conversiones de formato GIF a PPTX al tiempo que conserva el contenido estructural y lógico principal de la hoja de cálculo GIF de origen. Nuestra biblioteca NodeJS proporciona una solución profesional para convertir archivos GIF a PPTX en línea. Este Cloud SDK brinda a los desarrolladores de NodeJS una potente funcionalidad y garantiza una salida PPTX de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código NodeJS para convertir GIF a PPTX usando Cells Cloud SDK" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.gif"),
        format: "pptx",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir GIF a PPTX usando la biblioteca Cells Cloud NodeJS." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca NodeJS y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en JavaScript.</li>
<li>Utilice el método `putConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>nodo v6.17.1 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
