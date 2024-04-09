---
title: 使用 PHP 将 TXT 保存为 PPTX
description: 利用Aspose.Cells Cloud SDK for PHP将TXT格式文件保存为PPTX格式文件。
kwords: Excel, Save TXT as PPTX, REST, PHP
howto: How to save TXT as PPTX using Aspose.Cells Cloud PHP library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 TXT 保存为 PPTX" h2="PHP 用于将 TXT 保存为 PPTX 的库" p="使用Cells云的SaveAs API在PHP中创建自定义电子表格工作流程。这是使用PHP在线将TXT保存为PPTX和其他文档格式的专业解决方案。" urlsection="saveas/txt-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="将TXT文件另存为PHP中的PPTX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 TXT 文件格式另存为 PPTX 是一项复杂的任务。所有 TXT 到 PPTX 格式的转换均由我们的 PHP SDK 执行，同时保留源 TXT 电子表格的主要结构和逻辑内容。我们的 PHP 库是在线将 TXT 保存为 PPTX 文件的专业解决方案。该Cloud SDK为PHP开发者提供了强大的功能和完美的PPTX输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP 使用 REST 将 TXT 保存为 PPTX 的代码示例 API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.txt';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "pptx";
    $newfilename = "Book1Saveas.pptx";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud PHP 库将 TXT 另存为 PPTX。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 PHP 库并将引用（导入库）添加到您的项目中。</li>
<li>打开PHP中的源文件。</li>
<li>使用 `PostWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
