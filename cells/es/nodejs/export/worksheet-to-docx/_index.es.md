﻿---
title:  Exportar HOJA DE TRABAJO a DOCX desde una hoja de cálculo usando NodeJS API
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} mediante {2}.
url: /es/nodejs/export/worksheet-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API para exportar HOJA DE TRABAJO a archivo DOCX" h2="Biblioteca NodeJS para exportar HOJA DE TRABAJO a archivo DOCX" p="Use Cells Exportar REST API para exportar flujos de trabajo de objetos internos de hojas de cálculo en NodeJS. Esta es una solución profesional para exportar la HOJA DE TRABAJO a un archivo de formato DOCX desde una hoja de cálculo en línea usando NodeJS." urlsection="export/worksheet-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exportar objeto HOJA DE TRABAJO a archivo de formato DOCX en NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar un objeto HOJA DE TRABAJO a un archivo DOCX desde una hoja de cálculo es una tarea compleja. La exportación de HOJA DE TRABAJO a las transiciones de formato DOCX se realiza mediante nuestro SDK de NodeJS mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo de origen. Nuestra biblioteca NodeJS es una solución profesional para exportar objetos de HOJA DE TRABAJO a archivos de formato DOCX en línea. Este SDK de Cloud brinda a los desarrolladores de NodeJS una funcionalidad poderosa y una salida DOCX perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en NodeJS usando REST API para exportar HOJA DE TRABAJO a formato DOCX desde una hoja de cálculo" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { LightCellsApi, PostExportRequest } = require("asposecellscloud");
    const localPath = "C:/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new LightCellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    const AssemblyTestXlsx = "assemblytest.xlsx";
    var dataAssemblyTestXlsx =fs.createReadStream(localPath  + AssemblyTestXlsx);
    const DataSourceXlsx = "datasource.xlsx";
    var dataDataSourceXlsx =fs.createReadStream(localPath  + DataSourceXlsx);
    var req = new PostExportRequest({
      file:{AssemblyTestXlsx:dataAssemblyTestXlsx ,DataSourceXlsx:dataDataSourceXlsx },
      objectType : "worksheet",
      format: "docx",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar el nodo API para exportar la HOJA DE TRABAJO a DOCX" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método postExport para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>nodo v6.17.1 o posterior</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}