---
title:  Konvertera FODS till XLSX i molnet via PHP
description: Skapa, redigera eller konvertera Excel-filer med REST API & Open Source PHP SDK
url: /sv/php/conversion/fods-to-xlsx/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: XLSX
platform: PHP
otherformats: SVG MHTML XLTM XLTX XLSB XLSM DIF XLSX TXT PDF ODS TSV CSV XML XPS FODS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertera FODS till XLSX med PHP" h2="Automatisera Excel & OpenOffice-filkonvertering med open source Cloud SDK för PHP" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertera snabbt FODS till XLSX via PHP" %}}
1.  Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation
1. Initiera ```CellsApi``` med klient-id, klienthemlighet, basadress och API-version
1. Ladda upp FODS-fil till standardmolnlagring med metoden ```CellsApi.uploadFile```
1. Ring ```CellsApi.cellsSaveAsPostDocumentSaveAs``` för att få den resulterande XLSX-filen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Kom igång med Excel API & PHP SDK" %}}
 Hämta Excel Cloud SDK för PHP källkod från[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) för att kompilera SDK själv eller gå till[Släpps](https://releases.aspose.cloud/) för alternativa nedladdningsalternativ.

 Ta också en titt på Swagger-baserad[API Referens](https://apireference.aspose.cloud/cells/) att veta mer om[Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Kod för FODS till XLSX-konvertering" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.xlsx";
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