﻿---
title:  Salva XLSX come SVG API per PHP
description:  API cloud e SDK per Microsoft Excel e OpenOffice Calc. Converti foglio di calcolo in un altro file di formato.
url: /it/php/saveas/xlsx-to-svg/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API per salvare XLSX come SVG" h2="PHP libreria per salvare XLSX come SVG" p="Usa Cells SaveAs REST API per creare flussi di lavoro di fogli di calcolo personalizzati in PHP. Questa è una soluzione professionale per salvare XLSX come SVG e altri formati di documenti online utilizzando PHP." urlsection="saveas/xlsx-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file XLSX come SVG in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da XLSX come SVG è un compito complesso. Tutte le transizioni di formato da XLSX a SVG vengono eseguite dal nostro SDK PHP mantenendo il contenuto strutturale e logico principale del foglio di calcolo XLSX di origine. La nostra libreria PHP è una soluzione professionale per salvare XLSX come file SVG online. Questo Cloud SDK offre agli sviluppatori PHP potenti funzionalità e un output SVG perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in PHP utilizzando REST API per salvare XLSX come formato SVG" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xlsx';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "svg";
    $newfilename = "Book1Saveas.svg";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare PHP API per salvare XLSX come SVG" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo cellsSaveAsPostDocumentSaveAs per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>PHP 7.4 o più recente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}