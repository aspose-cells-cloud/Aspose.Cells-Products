---
title: 使用 PHP 将 XML 保存为 TXT
description: 利用Aspose.Cells Cloud SDK for PHP将XML格式文件保存为TXT格式文件。
kwords: Excel, Save XML as TXT, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XML as TXT using the Cells Cloud PHP library.","description": "How to save XML as TXT using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/saveas/xml-to-txt/","step": [{ "@type": "HowToStep","name": "How to save XML as TXT using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xml-to-txt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XML as TXT using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xml-to-txt/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XML as TXT using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xml-to-txt/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to save XML as TXT using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xml-to-txt/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XML 保存为 TXT" h2="PHP 用于将 XML 保存为 TXT 的库" p="使用 Cells Cloud 的 SaveAs API 在 PHP 中创建自定义电子表格工作流程。这是使用 PHP 在线将 XML 保存为 TXT 和其他文档格式的专业解决方案。" urlsection="saveas/xml-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="将 XML 文件另存为 TXT 格式 PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XML 文件格式保存为 TXT 是一项复杂的任务。所有 XML 到 TXT 格式的转换均由我们的 PHP SDK 执行，同时保留源 XML 电子表格的主要结构和逻辑内容。我们的 PHP 库是在线将 XML 保存为 TXT 文件的专业解决方案。该Cloud SDK为PHP开发者提供了强大的功能和完美的TXT输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP 使用 REST 将 XML 保存为 TXT 的代码示例 API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xml';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "txt";
    $newfilename = "Book1Saveas.txt";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells 云 PHP 库将 XML 保存为 TXT。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 PHP 库并将引用（导入库）添加到您的项目中。</li>
<li>打开PHP中的源文件。</li>
<li>使用 `PostWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
