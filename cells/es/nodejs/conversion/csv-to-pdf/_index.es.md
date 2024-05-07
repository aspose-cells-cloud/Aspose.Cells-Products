---
title:  Convierta CSV a PDF usando NodeJS
description:  Utilizar el SDK de la nube Aspose.Cells para NodeJS para convertir un archivo de formato CSV a un archivo de formato PDF.
kwords: Excel, Convert CSV to PDF, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert CSV to PDF using the Cells Cloud NodeJS library.","description": "How to convert CSV to PDF using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/conversion/csv-to-pdf/","step": [{ "@type": "HowToStep","name": "How to convert CSV to PDF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/csv-to-pdf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert CSV to PDF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/csv-to-pdf/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert CSV to PDF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/csv-to-pdf/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to convert CSV to PDF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/csv-to-pdf/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir CSV a PDF" h2="Biblioteca NodeJS para convertir CSV a PDF" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en proyectos NodeJS. Esta es una solución profesional para convertir CSV a PDF y otros formatos de documentos en línea usando NodeJS." urlsection="conversion/csv-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta CSV a PDF usando Cells Cloud SDK para NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de CSV a PDF puede ser una tarea compleja. Nuestro SDK de NodeJS maneja todas las conversiones de formato CSV a PDF mientras conserva el contenido estructural y lógico principal de la hoja de cálculo CSV de origen. Nuestra biblioteca NodeJS proporciona una solución profesional para convertir archivos CSV a PDF en línea. Este SDK de nube brinda a los desarrolladores de NodeJS una potente funcionalidad y garantiza resultados PDF de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código NodeJS para convertir CSV a PDF usando Cells Cloud SDK" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.csv"),
        format: "pdf",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo convertir CSV a PDF usando la biblioteca Cells Cloud NodeJS." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca NodeJS y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en JavaScript.</li>
<li>Utilice el método `putConvertWorkbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>nodo v6.17.1 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
