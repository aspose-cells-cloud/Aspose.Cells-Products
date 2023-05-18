﻿---
title:  MHTML in XLSM Converti API per C#
description:  API cloud e SDK per Microsoft Excel e OpenOffice Calc. Converti foglio di calcolo in un altro file di formato.
url: /it/net/conversion/mhtml-to-xlsm/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API per convertire MHTML in XLSM" h2="C# libreria per convertire MHTML in XLSM" p="Usa Cells Conversion REST API per creare flussi di lavoro di fogli di calcolo personalizzati in Net. Questa è una soluzione professionale per convertire MHTML in XLSM e altri formati di documenti online utilizzando C#." urlsection="conversion/mhtml-to-xlsm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti un file MHTML in XLSM in C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da MHTML a XLSM è un'attività complessa. Tutte le transizioni di formato da MHTML a XLSM vengono eseguite dal nostro SDK C# mantenendo il principale contenuto strutturale e logico del foglio di calcolo MHTML di origine. La nostra libreria C# è una soluzione professionale per convertire file MHTML in XLSM online. Questo Cloud SDK offre agli sviluppatori C# potenti funzionalità e un perfetto output XLSM.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in C# utilizzando REST API per convertire MHTML in formato XLSM" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.mhtml";
    string format = "xlsm";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xlsm";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare C# API per convertire MHTML in XLSM" >}}
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