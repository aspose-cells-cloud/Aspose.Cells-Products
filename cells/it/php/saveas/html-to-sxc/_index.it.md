﻿---
title:  Salva HTML come SXC utilizzando PHP
description:  Utilizzando Aspose.Cells Cloud SDK per PHP per salvare il file in formato HTML come file in formato SXC.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Salva HTML come SXC" h2="Libreria PHP per salvare HTML come SXC" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati per fogli di calcolo in PHP. Si tratta di una soluzione professionale per salvare HTML come SXC e altri formati di documenti online utilizzando PHP." urlsection="saveas/html-to-sxc/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file HTML come SXC in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da HTML come SXC è un compito complesso. Tutte le transizioni dal formato HTML al formato SXC vengono eseguite dal nostro SDK PHP mantenendo il contenuto strutturale e logico principale del foglio di calcolo sorgente HTML. La nostra libreria PHP è una soluzione professionale per salvare HTML come file SXC online. Questo Cloud SDK offre agli sviluppatori PHP funzionalità potenti e un output SXC perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP Codice Esempio per salvare HTML come SXC utilizzando REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.html';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "sxc";
    $newfilename = "Book1Saveas.sxc";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per PHP per salvare i file Excel in altri formati HTML come SXC" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `PostWorkbookSaveAs` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>PHP 7.4 o successiva</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
