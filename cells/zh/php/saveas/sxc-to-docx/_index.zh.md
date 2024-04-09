---
title: 使用 PHP 将 SXC 保存为 DOCX
description: 利用Aspose.Cells Cloud SDK for PHP将SXC格式文件保存为DOCX格式文件。
kwords: Excel, Save SXC as DOCX, REST, PHP
howto: How to save SXC as DOCX using Aspose.Cells Cloud PHP library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将SXC另存为DOCX" h2="PHP 用于将 SXC 保存为 DOCX 的库" p="使用Cells云的SaveAs API在PHP中创建自定义电子表格工作流程。这是使用PHP在线将SXC保存为DOCX和其他文档格式的专业解决方案。" urlsection="saveas/sxc-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="在 PHP 中将 SXC 文件另存为 DOCX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 SXC 中的文件格式保存为 DOCX 是一项复杂的任务。所有 SXC 到 DOCX 格式的转换均由我们的 PHP SDK 执行，同时保留源 SXC 电子表格的主要结构和逻辑内容。我们的 PHP 库是在线将 SXC 保存为 DOCX 文件的专业解决方案。该Cloud SDK为PHP开发者提供了强大的功能和完美的DOCX输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP 使用 REST 将 SXC 保存为 DOCX 的代码示例 API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.sxc';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "docx";
    $newfilename = "Book1Saveas.docx";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud PHP 库将 SXC 另存为 DOCX。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 PHP 库并将引用（导入库）添加到您的项目中。</li>
<li>打开PHP中的源文件。</li>
<li>使用 `PostWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
