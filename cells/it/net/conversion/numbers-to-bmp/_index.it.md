---
title:  Converti i NUMERI in BMP utilizzando C#
description:  Utilizzando Aspose.Cells Cloud SDK per C# per convertire un file in formato NUMERI in un file in formato BMP.
kwords: Excel, Convert NUMBERS to BMP, REST, C#
howto: How to convert NUMBERS to BMP using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti i NUMERI in BMP" h2="Libreria C# per convertire i NUMERI in BMP" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Net. Questa è una soluzione professionale per convertire i NUMERI in BMP e altri formati di documenti online utilizzando C#." urlsection="conversion/numbers-to-bmp/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti NUMERI in BMP utilizzando Cells Cloud SDK per C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da NUMBERS a BMP può essere un compito complesso. Il nostro SDK C# gestisce tutte le conversioni del formato NUMBERS in BMP preservando il contenuto strutturale e logico principale del foglio di calcolo NUMBERS di origine. La nostra libreria C# fornisce una soluzione professionale per convertire online i file NUMBERS in BMP. Questo Cloud SDK offre agli sviluppatori C# potenti funzionalità e garantisce un output BMP di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Esempio di codice per convertire i NUMERI in BMP utilizzando Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string format = "bmp";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.bmp";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Scopri come convertire i NUMERI in BMP utilizzando la libreria Cells Cloud Net." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria C# e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in C#</li>
<li>Utilizza il metodo `PutConvertWorkbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>NET Framework 4.5.2 o successiva</li>
<li>Net Standard 2.0 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
