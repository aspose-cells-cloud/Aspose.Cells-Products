---
title: Export Workbook to WMF file via PHP
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Export workbok or interanl object to kinds of format file in the Cloud.
url: /php/export/workbook-to-wmf/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Export Workbook to WMF file in the Cloud" h2="Excel & OpenOffice spreadsheet export with open source Cloud SDK for PHP">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export Workbook to WMF file in Cloud SDK for PHP " %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```LightCellsAPI``` with Client Id, Client Secret, Base URL & API version
1. Call ```postExport``` method to get the resultant WMF stream
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for .NET source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) to compile the SDK yourself or head to the [Releases](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/releases) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/#/LightCells/PostExport) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Code for WORKBOOK to WMF Conversion" gistPath="" %}}
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
<?php
require_once('vendor\autoload.php');
use \Aspose\Cells\Cloud\Api\LightCellsApi;
$cells = new LightCellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
$files = array (
    'DataSource' =>  "C:/datasource.xlsx",
    'AssemblyTest' => "C:/assemblytest.xlsx"
);
$result = $cells->postExport( $files,'workbook', 'wmf' );
$filename = $result->getFiles()[0]->getFilename() ;
$fileData = $result->getFiles()[0]->getFileContent() ;
$ptr = fopen($filename, 'wb');
fwrite($ptr, base64_decode($fileData));
fclose($ptr);
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{% blocks/products/cells/cells-cloud-api-run-export  InputFormat="xlsx,*.xls,*.csv,*.txt,*.ods"  OutputFormat=wmf  ExportObjectType=workbook %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
