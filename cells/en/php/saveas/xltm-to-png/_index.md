---
title: Save XLTM as PNG using PHP 
description: Utilizing Aspose.Cells Cloud SDK for PHP to save XLTM format file as PNG format file. 
kwords: Excel, Save XLTM as PNG, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLTM as PNG using the Cells Cloud PHP library.","description": "How to save XLTM as PNG using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/saveas/xltm-to-png/","step": [{ "@type": "HowToStep","name": "How to save XLTM as PNG using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xltm-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLTM as PNG using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xltm-to-png/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLTM as PNG using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xltm-to-png/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to save XLTM as PNG using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xltm-to-png/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Save XLTM as PNG" h2="PHP library for saving XLTM as PNG" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in PHP. This is a professional solution to save XLTM as PNG and other document formats online using PHP." urlsection="saveas/xltm-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a XLTM file as PNG in PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLTM as PNG is a complex task. All XLTM to PNG format transitions is performed by our PHP SDK while maintaining the source XLTM spreadsheet's main structural and logical content. Our PHP library is a professional solution to save XLTM as PNG files online. This Cloud SDK gives PHP developers powerful functionality and perfect PNG output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Code Example for saving XLTM as PNG using REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xltm';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "png";
    $newfilename = "Book1Saveas.png";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to save XLTM as PNG using the Cells Cloud PHP library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install PHP library and add the reference (import the library) to your project.</li>
<li>Open the source file in PHP.</li>
<li>Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>PHP 7.4 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
