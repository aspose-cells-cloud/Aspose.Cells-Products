﻿---
title:  NUMBERS in MHTML Converti API in C#
description:  API cloud e SDK per Microsoft Excel e OpenOffice Calc. Converti foglio di calcolo in un altro file di formato.
url: /it/net/conversion/numbers-to-mhtml/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API per convertire NUMBERS in MHTML" h2="C# libreria per convertire NUMBERS in MHTML" p="Usa Cells Conversion REST API per creare flussi di lavoro di fogli di calcolo personalizzati in Net. Questa è una soluzione professionale per convertire NUMBERS in MHTML e altri formati di documenti online utilizzando C#." urlsection="conversion/numbers-to-mhtml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti un file NUMBERS in MHTML in C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da NUMBERS a MHTML è un'attività complessa. Tutte le transizioni dal formato NUMBERS al formato MHTML vengono eseguite dal nostro SDK C# mantenendo il contenuto strutturale e logico principale del foglio di calcolo NUMBERS sorgente. La nostra libreria C# è una soluzione professionale per convertire NUMBERS in file MHTML online. Questo Cloud SDK offre agli sviluppatori C# potenti funzionalità e un output MHTML perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in C# utilizzando REST API per convertire NUMBERS in formato MHTML" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string format = "mhtml";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.mhtml";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come usare C# API per convertire NUMBERS in MHTML" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo CellsWorkbookPutConvertWorkbook per ottenere il flusso risultante</li>
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