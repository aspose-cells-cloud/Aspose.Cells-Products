﻿---
title:  XLSM till PDF Konvertera API till PHP
description:  Använder Aspose.Cells Cloud SDK för PHP för att konvertera fil i XLSM-format till fil i PDF-format.
url: /sv/php/conversion/xlsm-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API för att konvertera XLSM till PDF" h2="PHP bibliotek för att konvertera XLSM till PDF" p="Använd Cells Conversion REST API för att skapa anpassade arbetsflöden för kalkylblad i PHP. Detta är en professionell lösning för att konvertera XLSM till PDF och andra dokumentformat online med PHP." urlsection="conversion/xlsm-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera en XLSM-fil till PDF i PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLSM till PDF är en komplex uppgift. Alla formatövergångar från XLSM till PDF utförs av vår PHP SDK samtidigt som källbladets XLSM-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt PHP-bibliotek är en professionell lösning för att konvertera XLSM till PDF-filer online. Denna Cloud SDK ger PHP-utvecklare kraftfull funktionalitet och perfekt PDF-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i PHP med REST API för att konvertera XLSM till PDF-format" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xlsm';    
    $format ='pdf';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.pdf", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder PHP API för att konvertera XLSM till PDF" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Ring cellsWorkbookPutConvertWorkBook-metoden för att få den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>PHP 7.4 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}