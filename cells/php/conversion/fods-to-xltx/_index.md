---
title: Convert FODS to XLTX in the Cloud via PHP 
description: Create, Edit or Convert Excel files with REST API & Open Source PHP SDK
url: /php/conversion/fods-to-xltx/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: XLTX
platform: PHP
otherformats: XPS XML MD MHTML XLSB XLTX SVG DIF TIFF FODS PDF XLTM XLSX TSV CSV XLSM 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert FODS to XLTX with PHP" h2="Automate Excel & OpenOffice file conversion with open source Cloud SDK for PHP">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Quickly Convert FODS to XLTX via PHP" %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApi``` with Client Id, Client Secret, Base URL & API version
1. Upload FODS file to default Cloud Storage with ```CellsApi.uploadFile``` method
1. Call ```CellsApi.cellsSaveAsPostDocumentSaveAs``` to get the resultant XLTX file
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel API & PHP SDK" %}}
Get Excel Cloud SDK for PHP source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) to compile the SDK yourself or head to the [Releases](https://releases.aspose.cloud/) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Code for FODS to XLTX Conversion" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.xltx";
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