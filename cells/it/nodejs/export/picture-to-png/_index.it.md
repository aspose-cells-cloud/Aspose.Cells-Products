---
title:  Esporta IMMAGINE a PNG da Excel utilizzando Cells Cloud SDK per NodeJS
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Esporta IMMAGINE a PNG da Excel" h2="Libreria NodeJS per esportare IMMAGINE nel file PNG" p="Utilizza Export API of Cells Cloud per esportare i flussi di lavoro degli oggetti interni del file Excel in NodeJS. Questa è una soluzione professionale per esportare IMMAGINE nel file in formato PNG da un foglio di calcolo online utilizzando NodeJS." urlsection="export/picture-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Esporta l\'oggetto IMMAGINE nel file in formato PNG utilizzando Cells Cloud SDK per NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto IMMAGINE nel file PNG dal file Excel è un'attività complessa. L'esportazione delle transizioni di formato IMMAGINE nel formato PNG viene eseguita dal nostro SDK NodeJS mantenendo il contenuto strutturale e logico principale del foglio di calcolo IMMAGINE di origine. La nostra libreria NodeJS è una soluzione professionale per esportare oggetti IMMAGINE in file in formato PNG online. Questo Cloud SDK offre agli sviluppatori NodeJS funzionalità potenti e un output PNG perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice in NodeJS utilizzando REST API per esportare IMMAGINE nel formato PNG dal foglio di calcolo" gistPath="" %}}
  
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
      objectType : "picture",
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK for Node per esportare oggetti da Excel PICTURE a PNG" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `postExport` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>nodo v6.17.1 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
