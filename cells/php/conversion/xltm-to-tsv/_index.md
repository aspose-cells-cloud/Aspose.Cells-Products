---
title: Convert XLTM to TSV in the Cloud via PHP 
description: Create, Edit or Convert Excel files with REST API & Open Source PHP SDK
url: /php/conversion/xltm-to-tsv/
family: cells
platformtag: php
feature: conversion
informat: XLTM
outformat: TSV
platform: PHP
otherformats: DIF HTML XLS XLTX ODS CSV XLSM XLSB XML MD SVG XLSX TSV SXC MHTML TXT 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XLTM to TSV with PHP" h2="Automate Excel & OpenOffice file conversion with open source Cloud SDK for PHP">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Quickly Convert XLTM to TSV via PHP" %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApi``` with Client Id, Client Secret, Base URL & API version
1. Upload XLTM file to default Cloud Storage with ```CellsApi.uploadFile``` method
1. Call ```CellsApi.cellsSaveAsPostDocumentSaveAs``` to get the resultant TSV file
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel API & PHP SDK" %}}
Get Excel Cloud SDK for PHP source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) to compile the SDK yourself or head to the [Releases](https://releases.aspose.cloud/) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Code for XLTM to TSV Conversion" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.xltm';    
$saveOptions = null;
$newfilename = "output.tsv";
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