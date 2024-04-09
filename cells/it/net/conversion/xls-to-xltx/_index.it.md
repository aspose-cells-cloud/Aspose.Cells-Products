---
title:  Converti XLS in XLTX utilizzando C#
description:  Utilizzando Aspose.Cells Cloud SDK per C# per convertire un file in formato XLS in un file in formato XLTX.
kwords: Excel, Convert XLS to XLTX, REST, C#
howto: How to convert XLS to XLTX using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti XLS in XLTX" h2="C# libreria per convertire XLS in XLTX" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Net. Questa è una soluzione professionale per convertire XLS in XLTX e altri formati di documenti online utilizzando C#." urlsection="conversion/xls-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti XLS in XLTX utilizzando Cells Cloud SDK per C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da XLS a XLTX può essere un compito complesso. Il nostro SDK C# gestisce tutte le conversioni del formato XLS in XLTX preservando il contenuto strutturale e logico principale del foglio di calcolo XLS di origine. La nostra libreria C# fornisce una soluzione professionale per convertire online file XLS in XLTX. Questo Cloud SDK offre agli sviluppatori C# potenti funzionalità e garantisce output XLTX di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Esempio di codice per convertire XLS in XLTX utilizzando Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xls";
    string format = "xltx";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xltx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Scopri come convertire XLS in XLTX utilizzando la libreria Cloud Net Cells." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria C# e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in C#</li>
<li>Utilizza il metodo `PutConvertWorkbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>NET Framework 4.5.2 o successiva</li>
<li>Net Standard 2.0 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
