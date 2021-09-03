---
title: Convert XLTM to MHTML in the Cloud via PHP 
description: Create, Edit or Convert Excel files with REST API & Open Source PHP SDK
url: /php/conversion/xltm-to-mhtml/
family: cells
platformtag: php
feature: conversion
informat: XLTM
outformat: MHTML
platform: PHP
otherformats: DIF SXC MD XLT CSV XML XLSB FODS XLSX XLTX XPS XLSM PDF TXT MHTML TIFF 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XLTM to MHTML with PHP" h2="Automate Excel & OpenOffice file conversion with open source Cloud SDK for PHP">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Quickly Convert XLTM to MHTML via PHP" %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApi``` with Client Id, Client Secret, Base URL & API version
1. Upload XLTM file to default Cloud Storage with ```CellsApi.uploadFile``` method
1. Call ```CellsApi.cellsSaveAsPostDocumentSaveAs``` to get the resultant MHTML file
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel API & PHP SDK" %}}
Get Excel Cloud SDK for PHP source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) to compile the SDK yourself or head to the [Releases](https://releases.aspose.cloud/) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Code for XLTM to MHTML Conversion" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.xltm';    
$saveOptions = null;
$newfilename = "output.mhtml";
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