---
title: Export CHART to WMF from Excel using Cells Cloud SDK for PHP  
description: Aspose.Cells Cloud REST API support exporting {0} to {1} format files using {2}. 
kwords: Excel, chart, wmf, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for PHP to export objects from Excel CHART to WMF","description": "How to use Cells Cloud SDK for PHP to export objects from Excel CHART to WMF","image": {"@type": "ImageObject"},"url": "/php/export/chart-to-wmf/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel CHART to WMF step 1", "image": {"@type": "ImageObject",},"url": "/php/export/chart-to-wmf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel CHART to WMF step 1", "image": {"@type": "ImageObject",},"url": "/php/export/chart-to-wmf/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for PHP to export objects from Excel CHART to WMF step 1", "image": {"@type": "ImageObject",},"url": "/php/export/chart-to-wmf/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Export CHART to WMF from Excel" h2="PHP library for exporting CHART to WMF file" p="Use Export API of Cells Cloud to export Excel file internal object workflows in PHP. This is a professional solution to export CHART to WMF format file from spreadsheet online using PHP." urlsection="export/chart-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Export CHART object to WMF format file using Cells Cloud SDK for PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST %}}
<br/>
Export CHART object to WMF file from Excel file is a complex task. Export CHART to WMF format transitions is performed by our PHP SDK while maintaining the source CHART spreadsheet's main structural and logical content. Our PHP library is a professional solution to export CHART objects to WMF format files online. This Cloud SDK gives PHP developers powerful functionality and perfect WMF output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Code example in PHP using REST API to export CHART to WMF format from spreadsheet" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'chart', 'wmf' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for PHP to export objects from Excel CHART to WMF" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Use the `postExport` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>PHP 7.4 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
