---
title: Save TSV as JPG API for PHP 
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Convert spreadsheet to other format file. 
url: /php/saveas/tsv-to-jpg/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API to save TSV as JPG" h2="PHP library to save TSV as JPG" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in PHP. This is a professional solution to save TSV as JPG and other document formats online using PHP." urlsection="saveas/tsv-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a TSV file as JPG in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from TSV as JPG is a complex task. All TSV to JPG format transitions is performed by our PHP SDK while maintaining the source TSV spreadsheet's main structural and logical content. Our PHP library is a professional solution to save TSV as JPG files online. This Cloud SDK gives PHP developers powerful functionality and perfect JPG output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in PHP using REST API to save TSV as JPG format" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.tsv';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "jpg";
    $newfilename = "Book1Saveas.jpg";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use PHP API to save  TSV as JPG" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cellsSaveAsPostDocumentSaveAs method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>PHP 7.4 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}