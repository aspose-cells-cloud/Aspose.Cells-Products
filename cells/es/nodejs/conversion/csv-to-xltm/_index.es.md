﻿---
title:  CSV a XLTM Convertir API para NodeJS
description:  Usando Aspose.Cells Cloud SDK para NodeJS para convertir un archivo de formato CSV a un archivo de formato XLTM.
url: /es/nodejs/conversion/csv-to-xltm/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API para convertir CSV a XLTM" h2="Biblioteca NodeJS para convertir CSV a XLTM" p="Use Cells Conversion REST API para crear flujos de trabajo de hojas de cálculo personalizados en NodeJS. Esta es una solución profesional para convertir CSV a XLTM y otros formatos de documentos en línea usando NodeJS." urlsection="conversion/csv-to-xltm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta un archivo CSV a XLTM en NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de CSV a XLTM es una tarea compleja. Todas las transiciones de formato CSV a XLTM se realizan mediante nuestro SDK de NodeJS mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo CSV de origen. Nuestra biblioteca NodeJS es una solución profesional para convertir archivos CSV a XLTM en línea. Este SDK de Cloud brinda a los desarrolladores de NodeJS una funcionalidad poderosa y una salida XLTM perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en NodeJS usando REST API para convertir CSV a formato XLTM" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.csv"),
        format: "xltm",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar el Nodo API para convertir CSV a XLTM" >}}
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