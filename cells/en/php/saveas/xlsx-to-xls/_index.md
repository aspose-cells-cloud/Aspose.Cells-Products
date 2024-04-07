---
title: Save XLSX as XLS using PHP 
description: Utilizing Aspose.Cells Cloud SDK for PHP to save XLSX format file as XLS format file. 
kwords: Excel, Save XLSX as XLS, REST, PHP
howto: How to save XLSX as XLS using Aspose.Cells Cloud PHP library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save XLSX as XLS" h2="PHP library for saving XLSX as XLS" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in PHP. This is a professional solution to save XLSX as XLS and other document formats online using PHP." urlsection="saveas/xlsx-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a XLSX file as XLS in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLSX as XLS is a complex task. All XLSX to XLS format transitions is performed by our PHP SDK while maintaining the source XLSX spreadsheet's main structural and logical content. Our PHP library is a professional solution to save XLSX as XLS files online. This Cloud SDK gives PHP developers powerful functionality and perfect XLS output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Code Example for saving XLSX as XLS using REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xlsx';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "xls";
    $newfilename = "Book1Saveas.xls";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save XLSX as XLS using the Cells Cloud PHP library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install PHP library and add the reference (import the library) to your project.</li>
<li>Open the source file in PHP.</li>
<li>Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>PHP 7.4 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
