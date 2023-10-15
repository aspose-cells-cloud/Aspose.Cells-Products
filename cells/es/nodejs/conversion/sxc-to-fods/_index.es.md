---
title:  Convierta SXC a FODS usando NodeJS
description:  Utilizar el SDK de nube Aspose.Cells para NodeJS para convertir un archivo de formato SXC a un archivo de formato FODS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir SXC a FODS" h2="Biblioteca NodeJS para convertir SXC a FODS" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en proyectos NodeJS. Esta es una solución profesional para convertir SXC a FODS y otros formatos de documentos en línea usando NodeJS." urlsection="conversion/sxc-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta SXC a FODS usando Cells Cloud SDK para NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de SXC a FODS puede ser una tarea compleja. Nuestro SDK de NodeJS maneja todas las conversiones de formato SXC a FODS mientras preserva el contenido estructural y lógico principal de la hoja de cálculo SXC de origen. Nuestra biblioteca NodeJS proporciona una solución profesional para convertir archivos SXC a FODS en línea. Este Cloud SDK brinda a los desarrolladores de NodeJS una potente funcionalidad y garantiza resultados FODS de alta calidad.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código NodeJS para convertir SXC a FODS usando Cells Cloud SDK" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.sxc"),
        format: "fods",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Node para convertir archivos Excel a otros formatos SXC a FODS" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `putConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>nodo v6.17.1 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
