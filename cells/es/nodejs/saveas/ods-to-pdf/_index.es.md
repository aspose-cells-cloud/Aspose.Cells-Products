﻿---
title: Guardar ODS como PDF API para NodeJS
description:  Usando Aspose.Cells Cloud SDK para NodeJS para guardar el archivo de formato ODS como archivo de formato PDF.
url: /es/nodejs/saveas/ods-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API para guardar ODS como PDF" h2="Biblioteca NodeJS para guardar ODS como PDF" p="Use Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en NodeJS. Esta es una solución profesional para guardar ODS como PDF y otros formatos de documentos en línea usando NodeJS." urlsection="saveas/ods-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo ODS como PDF en NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de ODS como PDF es una tarea compleja. Todas las transiciones de formato ODS a PDF se realizan mediante nuestro SDK de NodeJS mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo ODS de origen. Nuestra biblioteca NodeJS es una solución profesional para guardar ODS como archivos PDF en línea. Este SDK de Cloud brinda a los desarrolladores de NodeJS una funcionalidad poderosa y un resultado PDF perfecto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en NodeJS usando REST API para guardar ODS como formato PDF" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.ods",
      folder: "CellsTests",
      newfilename: "Book1Saveas.pdf",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar el Nodo API para guardar ODS como PDF" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método cellSaveAsPostDocumentSaveAs para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>nodo v6.17.1 o posterior</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}