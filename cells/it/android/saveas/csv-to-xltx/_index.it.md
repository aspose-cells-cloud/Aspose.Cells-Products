﻿---
title:  Salva CSV come XLTX utilizzando Android
description:  Utilizzando Aspose.Cells Cloud SDK per Android per salvare il file in formato CSV come file in formato XLTX.
kwords: Excel, Save CSV as XLTX, REST, Android
howto: How to save CSV as XLTX using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Salva CSV come XLTX" h2="Libreria Android per salvare CSV come XLTX" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo in Android. Questa è una soluzione professionale per salvare CSV come XLTX e altri formati di documenti online utilizzando Android." urlsection="saveas/csv-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Salva un file CSV come XLTX in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da CSV come XLTX è un compito complesso. Tutte le transizioni dal formato CSV a XLTX vengono eseguite dal nostro SDK Android mantenendo il contenuto strutturale e logico principale del foglio di calcolo CSV di origine. La nostra libreria Android è una soluzione professionale per salvare online CSV come file XLTX. Questo Cloud SDK offre agli sviluppatori Android funzionalità potenti e un output XLTX perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice Android per salvare CSV come XLTX utilizzando REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.csv";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xltx";
    String folder ="CellsTests";
    try
    {
        CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
        cellsApi.cellsSaveAsPostDocumentSaveAs(name , saveOptions,newfilename,false,false,folder,null,null,null,true);                       
    }
    catch(Exception exception )
    {
        System.out.print(exception);
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Android per salvare i file Excel in altri formati" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `postWorkbookSaveAs` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Android 7 o successivo</li>
<li>Java(TM) Ambiente runtime SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
