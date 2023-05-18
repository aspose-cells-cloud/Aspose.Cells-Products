﻿---
title:  Salva JPG come PDF API for Java
description:  API cloud e SDK per Microsoft Excel e OpenOffice Calc. Converti foglio di calcolo in un altro file di formato.
url: /it/java/saveas/jpg-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API per salvare JPG come PDF" h2="Java libreria per salvare JPG come PDF" p="Usa Cells SaveAs REST API per creare flussi di lavoro di fogli di calcolo personalizzati in Java. Questa è una soluzione professionale per salvare JPG come PDF e altri formati di documenti online utilizzando Java." urlsection="saveas/jpg-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file JPG come PDF in Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da JPG come PDF è un compito complesso. Tutte le transizioni di formato da JPG a PDF vengono eseguite dal nostro SDK Java mantenendo il contenuto strutturale e logico principale del foglio di calcolo JPG di origine. La nostra libreria Java è una soluzione professionale per salvare online i file JPG come PDF. Questo Cloud SDK offre agli sviluppatori Java potenti funzionalità e un output PDF perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Java utilizzando REST API per salvare JPG come formato PDF" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.jpg";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.pdf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Java API per salvare JPG come PDF" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo cellsSaveAsPostDocumentSaveAs per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Maven 2.2.0 o più recente</li>
<li>Java(TM) SE Ambiente di runtime</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}