---
title:  Convierta XLT a PDF usando NodeJS
description:  Utilizar el SDK de la nube Aspose.Cells para NodeJS para convertir un archivo de formato XLT a un archivo de formato PDF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir XLT a PDF" h2="Biblioteca NodeJS para convertir XLT a PDF" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en proyectos NodeJS. Esta es una solución profesional para convertir XLT a PDF y otros formatos de documentos en línea usando NodeJS." urlsection="conversion/xlt-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta XLT a PDF usando Cells Cloud SDK para NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de XLT a PDF puede ser una tarea compleja. Nuestro SDK de NodeJS maneja todas las conversiones de formato XLT a PDF mientras conserva el contenido estructural y lógico principal de la hoja de cálculo XLT de origen. Nuestra biblioteca NodeJS proporciona una solución profesional para convertir archivos XLT a PDF en línea. Este SDK de nube brinda a los desarrolladores de NodeJS una potente funcionalidad y garantiza resultados PDF de alta calidad.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código NodeJS para convertir XLT a PDF usando Cells Cloud SDK" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xlt"),
        format: "pdf",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Node para convertir archivos Excel a otros formatos XLT a PDF" >}}
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
