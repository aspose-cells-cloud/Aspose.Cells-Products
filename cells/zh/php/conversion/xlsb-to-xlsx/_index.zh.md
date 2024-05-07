---
title: 使用 PHP 将 XLSB 转换为 XLSX
description: 利用PHP的Aspose.Cells Cloud SDK将XLSB格式文件转换为XLSX格式文件。
kwords: Excel, Convert XLSB to XLSX, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLSB to XLSX using the Cells Cloud PHP library.","description": "How to convert XLSB to XLSX using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/xlsb-to-xlsx/","step": [{ "@type": "HowToStep","name": "How to convert XLSB to XLSX using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xlsb-to-xlsx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLSB to XLSX using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xlsb-to-xlsx/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLSB to XLSX using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xlsb-to-xlsx/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert XLSB to XLSX using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/xlsb-to-xlsx/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLSB 转换为 XLSX" h2="PHP 用于将 XLSB 转换为 XLSX 的库" p="使用 Cells 云的转换 API 在 PHP 项目中创建自定义电子表格工作流程。这是使用 PHP 在线将 XLSB 转换为 XLSX 和其他文档格式的专业解决方案。" urlsection="conversion/xlsb-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for PHP 将 XLSB 转换为 XLSX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLSB 转换为 XLSX 可能是一项复杂的任务。我们的 PHP SDK 处理所有 XLSB 到 XLSX 格式的转换，同时保留源 XLSB 电子表格的主要结构和逻辑内容。我们的 PHP 库提供了在线将 XLSB 转换为 XLSX 文件的专业解决方案。该Cloud SDK为PHP开发者提供了强大的功能，并确保高质量的XLSX输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP 使用 Cells Cloud SDK 将 XLSB 转换为 XLSX 的代码示例" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xlsb';    
    $format ='xlsx';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xlsx", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells 云 PHP 库将 XLSB 转换为 XLSX。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 PHP 库并将引用（导入库）添加到您的项目中。</li>
<li>打开PHP中的源文件。</li>
<li>使用 `putConvertWorkbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
