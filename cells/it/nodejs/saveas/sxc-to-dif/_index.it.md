---
title:  Salva SXC come DIF API per NodeJS
description: Utilizzo di Aspose.Cells Cloud SDK for NodeJS per salvare il file in formato SXC come file in formato DIF.
url: /it/nodejs/saveas/sxc-to-dif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API per salvare SXC come DIF" h2="Libreria NodeJS per salvare SXC come DIF" p="Usa Cells SaveAs REST API per creare flussi di lavoro di fogli di calcolo personalizzati in NodeJS. Questa è una soluzione professionale per salvare SXC come DIF e altri formati di documenti online utilizzando NodeJS." urlsection="saveas/sxc-to-dif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file SXC come DIF in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da SXC come DIF è un compito complesso. Tutte le transizioni del formato da SXC a DIF vengono eseguite dal nostro NodeJS SDK mantenendo il contenuto strutturale e logico principale del foglio di calcolo SXC di origine. La nostra libreria NodeJS è una soluzione professionale per salvare SXC come file DIF online. Questo Cloud SDK offre agli sviluppatori NodeJS potenti funzionalità e un output DIF perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in NodeJS utilizzando REST API per salvare SXC come formato DIF" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.sxc",
      folder: "CellsTests",
      newfilename: "Book1Saveas.dif",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare il nodo API per salvare SXC come DIF" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo cellsSaveAsPostDocumentSaveAs per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>nodo v6.17.1 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
