---
title:  Converti FODS in TIFF nel Cloud via PHP
description: Crea, modifica o converti file Excel con REST API e SDK Open Source PHP
url: /it/php/conversion/fods-to-tiff/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: TIFF
platform: PHP
otherformats: CSV FODS TSV PDF TXT MHTML XLS DIF XLSX SVG XLSM XLTM XLTX XLSB XPS TIFF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertire FODS in TIFF con PHP" h2="Automatizza la conversione dei file Excel e OpenOffice con Cloud SDK open source per PHP" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Converti rapidamente FODS in TIFF via PHP" %}}
1.  Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione
1. Inizializza ```CellsApi``` con ID client, segreto client, URL di base e versione API
1. Carica il file FODS sul Cloud Storage predefinito con il metodo ```CellsApi.uploadFile```
1. Chiama lo ```CellsApi.cellsSaveAsPostDocumentSaveAs``` per ottenere il file TIFF risultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Inizia con Excel API e PHP SDK" %}}
 Ottieni Excel Cloud SDK per il codice sorgente PHP da[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) per compilare tu stesso l'SDK o vai al file[Rilasci](https://releases.aspose.cloud/) per opzioni di download alternative.

 Dai un'occhiata anche a Swagger-based[API Riferimento](https://apireference.aspose.cloud/cells/) per saperne di più su[Excel RESTO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Codice per FODS in TIFF Conversione" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.tiff";
$isAutoFitRows= 'true';
$isAutoFitColumns= 'true';
$folder = "Temp";
CellsApi::ready( $this->instance, $name, $folder );
$result = $this->instance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename, $isAutoFitRows, $isAutoFitColumns, $folder);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}