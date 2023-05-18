﻿---
title:  Esporta FOGLIO DI LAVORO in PDF dal foglio di calcolo utilizzando NodeJS API
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file Excel e oggetti interni in tipi di file di formato. L'SDK supporta i tipi di linguaggi di sviluppo. Includono Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby e swift.
url: /it/nodejs/export/worksheet-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API per esportare WORKSHEET nel file PDF" h2="Libreria NodeJS per esportare WORKSHEET nel file PDF" p="Utilizzare Cells Esporta REST API per esportare i flussi di lavoro degli oggetti interni del foglio di calcolo in NodeJS. Questa è una soluzione professionale per esportare FOGLIO DI LAVORO in file in formato PDF dal foglio di calcolo online utilizzando NodeJS." urlsection="export/worksheet-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Esporta l\'oggetto WORKSHEET nel file in formato PDF in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto WORKSHEET nel file PDF dal foglio di calcolo è un'attività complessa. L'esportazione del FOGLIO DI LAVORO nelle transizioni di formato PDF viene eseguita dal nostro SDK NodeJS mantenendo il contenuto strutturale e logico principale del foglio di calcolo del FOGLIO DI LAVORO di origine. La nostra libreria NodeJS è una soluzione professionale per esportare oggetti WORKSHEET in file in formato PDF online. Questo Cloud SDK offre agli sviluppatori NodeJS potenti funzionalità e un output PDF perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in NodeJS utilizzando REST API per esportare WORKSHEET nel formato PDF dal foglio di calcolo" gistPath="" %}}
  
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
      format: "pdf",
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare il nodo API per esportare WORKSHEET in PDF" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo postExport per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>nodo v6.17.1 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}