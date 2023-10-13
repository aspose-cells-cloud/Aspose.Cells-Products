﻿---
title: JSON a XLS Convertir API para NodeJS
description:  Usando Aspose.Cells Cloud SDK para NodeJS para convertir un archivo de formato JSON a un archivo de formato XLS.
url: /es/nodejs/conversion/json-to-xls/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API para convertir JSON a XLS" h2="Biblioteca NodeJS para convertir JSON a XLS" p="Use Cells Conversion REST API para crear flujos de trabajo de hojas de cálculo personalizados en NodeJS. Esta es una solución profesional para convertir JSON a XLS y otros formatos de documentos en línea usando NodeJS." urlsection="conversion/json-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un archivo JSON a XLS en NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de JSON a XLS es una tarea compleja. Nuestro SDK de NodeJS realiza todas las transiciones de formato JSON a XLS mientras mantiene el contenido estructural y lógico principal de la hoja de cálculo JSON de origen. Nuestra biblioteca NodeJS es una solución profesional para convertir archivos JSON a XLS en línea. Este SDK de Cloud brinda a los desarrolladores de NodeJS una funcionalidad poderosa y una salida XLS perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en NodeJS usando REST API para convertir JSON a formato XLS" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.json"),
        format: "xls",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar el nodo API para convertir JSON a XLS" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método cellsWorkbookPutConvertWorkbook para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>nodo v6.17.1 o posterior</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}