---
title: MHTML to TXT Convert API for PHP 
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Convert spreadsheet to other format file. 
url: /php/conversion/mhtml-to-txt/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API to convert MHTML to TXT" h2="PHP library to convert MHTML to TXT" p="Use Cells Conversion REST API to create customized spreadsheet workflows in PHP. This is a professional solution to convert MHTML to TXT and other document formats online using PHP." urlsection="conversion/mhtml-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert a MHTML file to TXT in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from MHTML to TXT is a complex task. All MHTML to TXT format transitions is performed by our PHP SDK while maintaining the source MHTML spreadsheet's main structural and logical content. Our PHP library is a professional solution to convert MHTML to TXT files online. This Cloud SDK gives PHP developers powerful functionality and perfect TXT output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in PHP using REST API to convert MHTML to TXT format" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.mhtml';    
    $format ='txt';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.txt", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use PHP API to convert  MHTML to TXT" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cellsWorkbookPutConvertWorkBook method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>PHP 7.4 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}