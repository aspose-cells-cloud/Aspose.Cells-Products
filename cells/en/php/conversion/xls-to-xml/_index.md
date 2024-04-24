---
title: Convert XLS to XML using PHP 
description: Utilizing the Aspose.Cells Cloud SDK for PHP to convert a XLS format file to a XML format file. 
kwords: Excel, Convert XLS to XML, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLS to XML using the Cells Cloud PHP library.","description": "How to convert XLS to XML using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/xls-to-xml/","step": [{ "@type": "HowToStep","name": "How to convert XLS to XML using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xls-to-xml/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLS to XML using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xls-to-xml/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLS to XML using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xls-to-xml/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert XLS to XML using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xls-to-xml/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert XLS to XML" h2="PHP library for converting XLS to XML" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in PHP projects. This is a professional solution to convert XLS to XML and other document formats online using PHP." urlsection="conversion/xls-to-xml/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert XLS to XML using Cells Cloud SDK for PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XLS to XML can be a complex task. Our PHP SDK handles all XLS to XML format conversions while preserving the main structural and logical content of the source XLS spreadsheet. Our PHP library provides a professional solution for converting XLS to XML files online. This Cloud SDK empowers PHP developers with powerful functionality and ensures high-quality XML output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Code Example for converting XLS to XML using Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xls';    
    $format ='xml';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xml", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to convert XLS to XML using the Cells Cloud PHP library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install PHP library and add the reference (import the library) to your project.</li>
<li>Open the source file in PHP.</li>
<li>Use the `putConvertWorkbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>PHP 7.4 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
