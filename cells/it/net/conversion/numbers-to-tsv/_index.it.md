---
title:  Converti NUMERI in TSV utilizzando C#
description: Utilizzando Aspose.Cells Cloud SDK per C# per convertire un file in formato NUMERI in un file in formato TSV.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Converti NUMERI in TSV" h2="Libreria C# per la conversione dei NUMERI in TSV" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Net. Questa è una soluzione professionale per convertire NUMBERS in TSV e altri formati di documenti online utilizzando C#." urlsection="conversion/numbers-to-tsv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti NUMERI in TSV utilizzando Cells Cloud SDK per C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da NUMBERS a TSV può essere un compito complesso. Il nostro SDK C# gestisce tutte le conversioni dal formato NUMBERS al formato TSV preservando il contenuto strutturale e logico principale del foglio di calcolo NUMBERS di origine. La nostra libreria C# fornisce una soluzione professionale per convertire online NUMBERS in file TSV. Questo Cloud SDK offre agli sviluppatori C# potenti funzionalità e garantisce output TSV di alta qualità.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Esempio di codice per convertire NUMERI in TSV utilizzando Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string format = "tsv";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.tsv";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK for Net per convertire i file Excel in altri formati NUMBERS in TSV" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `PutConvertWorkbook` per recuperare il flusso risultante.</li>
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
