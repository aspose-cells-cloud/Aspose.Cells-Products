---
title:  Guarde XLT como WMF usando NodeJS
description:  Utilizando Aspose.Cells Cloud SDK para NodeJS para guardar el archivo en formato XLT como archivo en formato WMF.
kwords: Excel, Save XLT as WMF, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLT as WMF using the Cells Cloud NodeJS library.","description": "How to save XLT as WMF using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/saveas/xlt-to-wmf/","step": [{ "@type": "HowToStep","name": "How to save XLT as WMF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xlt-to-wmf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLT as WMF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xlt-to-wmf/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLT as WMF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xlt-to-wmf/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to save XLT as WMF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xlt-to-wmf/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar XLT como WMF" h2="Biblioteca NodeJS para guardar XLT como WMF" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en NodeJS. Esta es una solución profesional para guardar XLT como WMF y otros formatos de documentos en línea usando NodeJS." urlsection="saveas/xlt-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo XLT como WMF en NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLT como WMF es una tarea compleja. Todas las transiciones de formato XLT a WMF las realiza nuestro SDK de NodeJS mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLT de origen. Nuestra biblioteca NodeJS es una solución profesional para guardar XLT como archivos WMF en línea. Este Cloud SDK ofrece a los desarrolladores de NodeJS una potente funcionalidad y una salida WMF perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código NodeJS para guardar XLT como WMF usando REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xlt",
      folder: "CellsTests",
      newfilename: "Book1Saveas.wmf",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo guardar XLT como WMF usando la biblioteca Cells Cloud NodeJS." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca NodeJS y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en JavaScript.</li>
<li>Utilice el método `PostWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>nodo v6.17.1 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
