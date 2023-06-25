---
title:  Salva NUMERI come XLT API per C#
description:  Utilizzo di Aspose.Cells Cloud SDK per C# per salvare il file in formato NUMBERS come file in formato XLT.
url: /it/net/saveas/numbers-to-xlt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API per salvare i NUMERI come XLT" h2="C# libreria per salvare NUMBERS come XLT" p="Usa Cells SaveAs REST API per creare flussi di lavoro di fogli di calcolo personalizzati in Net. Questa è una soluzione professionale per salvare NUMERI come XLT e altri formati di documenti online utilizzando C#." urlsection="saveas/numbers-to-xlt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file NUMBERS come XLT in C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da NUMBERS come XLT è un compito complesso. Tutte le transizioni dal formato NUMBERS al formato XLT vengono eseguite dal nostro SDK C# mantenendo il contenuto strutturale e logico principale del foglio di calcolo NUMBERS sorgente. La nostra libreria C# è una soluzione professionale per salvare i NUMERI come file XLT online. Questo Cloud SDK offre agli sviluppatori C# potenti funzionalità e un perfetto output XLT.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in C# utilizzando REST API per salvare NUMBERS come formato XLT" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string newfilename = "Book1SaveAs.xlt";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare C# API per salvare i NUMERI come XLT" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiamare il metodo CellsSaveAsPostDocumentSaveAs per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>NET Framework 4.5.2 o più recente</li>
<li>Net Standard 2.0 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
