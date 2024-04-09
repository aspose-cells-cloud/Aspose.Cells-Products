---
title:  Salva SXC come JSON utilizzando C#
description:  Utilizzando Aspose.Cells Cloud SDK per C# per salvare il file in formato SXC come file in formato JSON.
kwords: Excel, Save SXC as JSON, REST, C#
howto: How to save SXC as JSON using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Salva SXC come JSON" h2="Libreria C# per salvare SXC come JSON" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo in Net. Questa è una soluzione professionale per salvare SXC come JSON e altri formati di documenti online utilizzando C#." urlsection="saveas/sxc-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="Salva un file SXC come JSON in C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da SXC come JSON è un compito complesso. Tutte le transizioni dal formato SXC al formato JSON vengono eseguite dal nostro SDK C# mantenendo il contenuto strutturale e logico principale del foglio di calcolo SXC di origine. La nostra libreria C# è una soluzione professionale per salvare SXC come file JSON online. Questo Cloud SDK offre agli sviluppatori C# funzionalità potenti e un output JSON perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Esempio di codice per salvare SXC come JSON utilizzando REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.sxc";
    string newfilename = "Book1SaveAs.json";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Scopri come salvare SXC come JSON utilizzando la libreria Cloud Net Cells." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria C# e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in C#</li>
<li>Utilizza il metodo `PostWorkbookSaveAs` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>NET Framework 4.5.2 o successiva</li>
<li>Net Standard 2.0 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
