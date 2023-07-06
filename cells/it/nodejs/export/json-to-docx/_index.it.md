---
title: Esporta Json nel file DOCX via NodeJS
description: Aspose.Cells Cloud REST API supporta l'esportazione di file Excel e oggetti interni in tipi di file di formato. L'SDK supporta i tipi di linguaggi di sviluppo. Includono Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby e swift.
url: /it/nodejs/export/json-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Esporta JSON in file DOCX nel Cloud" h2="Excel ed esportazione di fogli di calcolo OpenOffice con Cloud SDK open source per NodeJS" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Esporta JSON in file DOCX in Cloud SDK per NodeJS" %}}
1.  Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione
1. Inizializza ```CellsApi``` con ID client, segreto client, URL di base e versione API
1. Chiama il metodo ```cellsWorkbookPutConvertWorkbook``` per ottenere il flusso DOCX risultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Inizia con Excel REST API" %}}
 Ottieni il codice sorgente Excel Cloud SDK for .NET da[Git Hub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-node) per compilare tu stesso l'SDK o vai al file[Rilasci](https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/releases) per opzioni di download alternative.

 Dai anche un'occhiata a Swagger-based[API Riferimento]() per saperne di più sul[Excel RIPOSO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Codice NodeJS per la conversione da JSON a DOCX" gistPath="" %}}
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
      file: fs.createReadStream(localPath + "datasource.xlsx"),
      format: "docx",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
      .then((result) => {
        console.log(result)
    });

```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
