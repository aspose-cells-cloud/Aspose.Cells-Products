---
title: Save ODS as PPTX API for PHP 
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Convert spreadsheet to other format file. 
url: /php/saveas/ods-to-pptx/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API to save ODS as PPTX" h2="PHP library to save ODS as PPTX" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in PHP. This is a professional solution to save ODS as PPTX and other document formats online using PHP." urlsection="saveas/ods-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a ODS file as PPTX in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from ODS as PPTX is a complex task. All ODS to PPTX format transitions is performed by our PHP SDK while maintaining the source ODS spreadsheet's main structural and logical content. Our PHP library is a professional solution to save ODS as PPTX files online. This Cloud SDK gives PHP developers powerful functionality and perfect PPTX output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in PHP using REST API to save ODS as PPTX format" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.ods';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "pptx";
    $newfilename = "Book1Saveas.pptx";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use PHP API to save  ODS as PPTX" >}}
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