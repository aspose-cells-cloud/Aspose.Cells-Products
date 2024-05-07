---
title:  Salva FODS come GIF utilizzando NodeJS
description:  Utilizzando Aspose.Cells Cloud SDK per NodeJS per salvare il file in formato FODS come file in formato GIF.
kwords: Excel, Save FODS as GIF, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save FODS as GIF using the Cells Cloud NodeJS library.","description": "How to save FODS as GIF using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/saveas/fods-to-gif/","step": [{ "@type": "HowToStep","name": "How to save FODS as GIF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/fods-to-gif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save FODS as GIF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/fods-to-gif/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save FODS as GIF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/fods-to-gif/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to save FODS as GIF using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/fods-to-gif/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Salva FODS come GIF" h2="Libreria NodeJS per salvare FODS come GIF" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati per fogli di calcolo in NodeJS. Questa è una soluzione professionale per salvare FODS come GIF e altri formati di documenti online utilizzando NodeJS." urlsection="saveas/fods-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Salva un file FODS come GIF in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da FODS come GIF è un compito complesso. Tutte le transizioni dal formato FODS al formato GIF vengono eseguite dal nostro SDK NodeJS mantenendo il contenuto strutturale e logico principale del foglio di calcolo FODS di origine. La nostra libreria NodeJS è una soluzione professionale per salvare FODS come file GIF online. Questo Cloud SDK offre agli sviluppatori NodeJS funzionalità potenti e un output GIF perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice NodeJS per salvare FODS come GIF utilizzando REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.fods",
      folder: "CellsTests",
      newfilename: "Book1Saveas.gif",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come salvare FODS come GIF utilizzando la libreria Cells Cloud NodeJS." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria NodeJS e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in JavaScript.</li>
<li>Utilizza il metodo `PostWorkbookSaveAs` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>nodo v6.17.1 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
