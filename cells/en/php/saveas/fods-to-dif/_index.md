---
title: Save FODS as DIF using PHP 
description: Utilizing Aspose.Cells Cloud SDK for PHP to save FODS format file as DIF format file. 
kwords: Excel, Save FODS as DIF, REST, PHP
howto: How to save FODS as DIF using Aspose.Cells Cloud PHP library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save FODS as DIF" h2="PHP library for saving FODS as DIF" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in PHP. This is a professional solution to save FODS as DIF and other document formats online using PHP." urlsection="saveas/fods-to-dif/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a FODS file as DIF in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from FODS as DIF is a complex task. All FODS to DIF format transitions is performed by our PHP SDK while maintaining the source FODS spreadsheet's main structural and logical content. Our PHP library is a professional solution to save FODS as DIF files online. This Cloud SDK gives PHP developers powerful functionality and perfect DIF output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Code Example for saving FODS as DIF using REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.fods';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "dif";
    $newfilename = "Book1Saveas.dif";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save FODS as DIF using the Cells Cloud PHP library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install PHP library and add the reference (import the library) to your project.</li>
<li>Open the source file in PHP.</li>
<li>Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>PHP 7.4 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
