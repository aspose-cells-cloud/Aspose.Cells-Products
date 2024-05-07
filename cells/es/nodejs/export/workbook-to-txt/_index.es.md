---
title: Exporte WORKBOOK a TXT desde Excel usando Cells Cloud SDK para NodeJS
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} usando {2}.
kwords: Excel, workbook, txt, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to TXT","description": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to TXT","image": {"@type": "ImageObject"},"url": "/nodejs/export/workbook-to-txt/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to TXT step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/workbook-to-txt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to TXT step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/workbook-to-txt/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel WORKBOOK to TXT step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/workbook-to-txt/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportar LIBRO DE TRABAJO a TXT desde Excel" h2="Biblioteca NodeJS para exportar WORKBOOK a archivo TXT" p="Utilice Exportar API de Cells Cloud para exportar flujos de trabajo de objetos internos de archivos Excel en NodeJS. Esta es una solución profesional para exportar WORKBOOK a un archivo en formato TXT desde una hoja de cálculo en línea usando NodeJS." urlsection="export/workbook-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporte el objeto WORKBOOK a un archivo en formato TXT usando Cells Cloud SDK para NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar el objeto WORKBOOK a un archivo TXT desde el archivo Excel es una tarea compleja. Nuestro SDK de NodeJS realiza la exportación de transiciones de WORKBOOK a formato TXT manteniendo el contenido estructural y lógico principal de la hoja de cálculo de WORKBOOK de origen. Nuestra biblioteca NodeJS es una solución profesional para exportar objetos WORKBOOK a archivos en formato TXT en línea. Este SDK en la nube ofrece a los desarrolladores de NodeJS una potente funcionalidad y una salida TXT perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código en NodeJS usando REST API para exportar WORKBOOK a formato TXT desde una hoja de cálculo" gistPath="" %}}
  
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
      objectType : "workbook",
      format: "txt",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Node para exportar objetos de Excel WORKBOOK a TXT" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `postExport` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>nodo v6.17.1 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
