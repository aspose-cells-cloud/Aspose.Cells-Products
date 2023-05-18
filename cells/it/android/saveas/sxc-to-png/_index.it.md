﻿---
title:  Salva SXC come PNG API per Android
description:  API cloud e SDK per Microsoft Excel e OpenOffice Calc. Converti foglio di calcolo in un altro file di formato.
url: /it/android/saveas/sxc-to-png/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API per salvare SXC come PNG" h2="Libreria Android per salvare SXC come PNG" p="Usa Cells SaveAs REST API per creare flussi di lavoro di fogli di calcolo personalizzati in Android. Questa è una soluzione professionale per salvare SXC come PNG e altri formati di documenti online utilizzando Android." urlsection="saveas/sxc-to-png/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file SXC come PNG in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Il salvataggio dei formati di file da SXC come PNG è un'attività complessa. Tutte le transizioni di formato da SXC a PNG vengono eseguite dal nostro SDK Android mantenendo il contenuto strutturale e logico principale del foglio di calcolo SXC di origine. La nostra libreria Android è una soluzione professionale per salvare SXC come file PNG online. Questo Cloud SDK offre agli sviluppatori Android potenti funzionalità e un output PNG perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Android utilizzando REST API per salvare SXC come formato PNG" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.sxc";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.png";
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
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Java API per salvare SXC come PNG" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo cellsSaveAsPostDocumentSaveAs per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Android 7 o più recente</li>
<li>Java(TM) SE Ambiente di runtime</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}