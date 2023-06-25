---
title: Save XLS as WMF API for PHP 
description: Using Aspose.Cells Cloud SDK for PHP to save XLS format file as WMF format file. 
url: /php/saveas/xls-to-wmf/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API to save XLS as WMF" h2="PHP library to save XLS as WMF" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in PHP. This is a professional solution to save XLS as WMF and other document formats online using PHP." urlsection="saveas/xls-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a XLS file as WMF in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLS as WMF is a complex task. All XLS to WMF format transitions is performed by our PHP SDK while maintaining the source XLS spreadsheet's main structural and logical content. Our PHP library is a professional solution to save XLS as WMF files online. This Cloud SDK gives PHP developers powerful functionality and perfect WMF output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in PHP using REST API to save XLS as WMF format" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xls';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "wmf";
    $newfilename = "Book1Saveas.wmf";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use PHP API to save  XLS as WMF" >}}
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
