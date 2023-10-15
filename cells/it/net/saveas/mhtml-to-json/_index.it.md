---
title:  Salva MHTML come JSON utilizzando C#
description:  Utilizzando Aspose.Cells Cloud SDK per C# per salvare il file in formato MHTML come file in formato JSON.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Salva MHTML come JSON" h2="Libreria C# per il salvataggio di MHTML come JSON" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo in Net. Questa è una soluzione professionale per salvare MHTML come JSON e altri formati di documenti online utilizzando C#." urlsection="saveas/mhtml-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file MHTML come JSON in C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare formati di file da MHTML come JSON è un compito complesso. Tutte le transizioni dal formato MHTML al formato JSON vengono eseguite dal nostro SDK C# mantenendo il contenuto strutturale e logico principale del foglio di calcolo MHTML di origine. La nostra libreria C# è una soluzione professionale per salvare MHTML come file JSON online. Questo Cloud SDK offre agli sviluppatori C# funzionalità potenti e un output JSON perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Esempio di codice per salvare MHTML come JSON utilizzando REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.mhtml";
    string newfilename = "Book1SaveAs.json";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK for Net per salvare i file Excel in altri formati MHTML come JSON" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `PostWorkbookSaveAs` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>NET Framework 4.5.2 o successiva</li>
<li>Net Standard 2.0 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
