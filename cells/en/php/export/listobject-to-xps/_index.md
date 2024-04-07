---
title: Export LISTOBJECT to XPS from Excel using Cells Cloud SDK for PHP  
description: Aspose.Cells Cloud REST API support exporting {0} to {1} format files using {2}. 
kwords: 
howto: 
---


{{< blocks/products/cells/cells-cloud-banner h1="Export LISTOBJECT to XPS from Excel" h2="PHP library for exporting LISTOBJECT to XPS file" p="Use Export API of Cells Cloud to export Excel file internal object workflows in PHP. This is a professional solution to export LISTOBJECT to XPS format file from spreadsheet online using PHP." urlsection="export/listobject-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Export LISTOBJECT object to XPS format file using Cells Cloud SDK for PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST %}}
<br/>
Export LISTOBJECT object to XPS file from Excel file is a complex task. Export LISTOBJECT to XPS format transitions is performed by our PHP SDK while maintaining the source LISTOBJECT spreadsheet's main structural and logical content. Our PHP library is a professional solution to export LISTOBJECT objects to XPS format files online. This Cloud SDK gives PHP developers powerful functionality and perfect XPS output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Code example in PHP using REST API to export LISTOBJECT to XPS format from spreadsheet" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'listobject', 'xps' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for PHP to export objects from Excel LISTOBJECT to XPS" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Use the `postExport` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>PHP 7.4 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
