---
title:  Converti XML in XPS utilizzando NodeJS
description:  Utilizzando Aspose.Cells Cloud SDK per NodeJS per convertire un file in formato XML in un file in formato XPS.
kwords: Excel, Convert XML to XPS, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XML to XPS using the Cells Cloud NodeJS library.","description": "How to convert XML to XPS using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/conversion/xml-to-xps/","step": [{ "@type": "HowToStep","name": "How to convert XML to XPS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xml-to-xps/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XML to XPS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xml-to-xps/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XML to XPS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xml-to-xps/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to convert XML to XPS using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/conversion/xml-to-xps/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti XML in XPS" h2="Libreria NodeJS per convertire XML in XPS" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati per fogli di calcolo nei progetti NodeJS. Questa è una soluzione professionale per convertire XML in XPS e altri formati di documenti online utilizzando NodeJS." urlsection="conversion/xml-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti XML in XPS utilizzando Cells Cloud SDK per NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da XML a XPS può essere un compito complesso. Il nostro SDK NodeJS gestisce tutte le conversioni del formato XML in XPS preservando il contenuto strutturale e logico principale del foglio di calcolo XML di origine. La nostra libreria NodeJS fornisce una soluzione professionale per convertire file XML in XPS online. Questo Cloud SDK offre agli sviluppatori NodeJS funzionalità potenti e garantisce un output XPS di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice NodeJS per convertire XML in XPS utilizzando Cells Cloud SDK" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xml"),
        format: "xps",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come convertire XML in XPS utilizzando la libreria Cells Cloud NodeJS." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria NodeJS e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in JavaScript.</li>
<li>Utilizza il metodo `putConvertWorkbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>nodo v6.17.1 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
