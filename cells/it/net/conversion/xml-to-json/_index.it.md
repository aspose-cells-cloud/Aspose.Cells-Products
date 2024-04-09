---
title:  Converti XML in JSON utilizzando C#
description:  Utilizzando Aspose.Cells Cloud SDK per C# per convertire un file in formato XML in un file in formato JSON.
kwords: Excel, Convert XML to JSON, REST, C#
howto: How to convert XML to JSON using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti XML in JSON" h2="Libreria C# per la conversione da XML a JSON" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Net. Questa è una soluzione professionale per convertire XML in JSON e altri formati di documenti online utilizzando C#." urlsection="conversion/xml-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti XML in JSON utilizzando Cells Cloud SDK per C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da XML a JSON può essere un compito complesso. Il nostro SDK C# gestisce tutte le conversioni del formato XML in JSON preservando il contenuto strutturale e logico principale del foglio di calcolo XML di origine. La nostra libreria C# fornisce una soluzione professionale per convertire file XML in JSON online. Questo Cloud SDK offre agli sviluppatori C# potenti funzionalità e garantisce un output JSON di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Esempio di codice per convertire XML in JSON utilizzando Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xml";
    string format = "json";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.json";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Scopri come convertire XML in JSON utilizzando la libreria Cloud Net Cells." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria C# e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in C#</li>
<li>Utilizza il metodo `PutConvertWorkbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>NET Framework 4.5.2 o successiva</li>
<li>Net Standard 2.0 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
