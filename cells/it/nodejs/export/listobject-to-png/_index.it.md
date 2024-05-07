---
title:  Esporta LISTOBJECT in PNG da Excel utilizzando Cells Cloud SDK per NodeJS
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
kwords: Excel, listobject, png, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Node to export objects from Excel LISTOBJECT to PNG","description": "How to use Cells Cloud SDK for Node to export objects from Excel LISTOBJECT to PNG","image": {"@type": "ImageObject"},"url": "/nodejs/export/listobject-to-png/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel LISTOBJECT to PNG step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/listobject-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel LISTOBJECT to PNG step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/listobject-to-png/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel LISTOBJECT to PNG step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/listobject-to-png/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Esporta LISTOBJECT a PNG da Excel" h2="Libreria NodeJS per esportare LISTOBJECT nel file PNG" p="Utilizza Export API of Cells Cloud per esportare i flussi di lavoro degli oggetti interni del file Excel in NodeJS. Questa è una soluzione professionale per esportare LISTOBJECT nel file in formato PNG da un foglio di calcolo online utilizzando NodeJS." urlsection="export/listobject-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Esporta l\'oggetto LISTOBJECT nel file in formato PNG utilizzando Cells Cloud SDK per NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto LISTOBJECT nel file PNG dal file Excel è un'attività complessa. L'esportazione di LISTOBJECT nelle transizioni di formato PNG viene eseguita dal nostro SDK NodeJS mantenendo il contenuto strutturale e logico principale del foglio di calcolo LISTOBJECT di origine. La nostra libreria NodeJS è una soluzione professionale per esportare online oggetti LISTOBJECT in file in formato PNG. Questo Cloud SDK offre agli sviluppatori NodeJS funzionalità potenti e un output PNG perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice in NodeJS utilizzando REST API per esportare LISTOBJECT nel formato PNG dal foglio di calcolo" gistPath="" %}}
  
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
      objectType : "listobject",
      format: "png",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK for Node per esportare oggetti da Excel LISTOBJECT a PNG" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `postExport` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>nodo v6.17.1 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
