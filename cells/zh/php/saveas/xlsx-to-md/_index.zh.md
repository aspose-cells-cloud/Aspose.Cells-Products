﻿---
title: 使用 PHP 将 XLSX 保存为 MD
description: 利用Aspose.Cells Cloud SDK for PHP将XLSX格式文件保存为MD格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 XLSX 保存为 MD" h2="PHP 用于将 XLSX 保存为 MD 的库" p="使用Cells云的SaveAs API在PHP中创建自定义电子表格工作流程。这是使用PHP在线将XLSX保存为MD和其他文档格式的专业解决方案。" urlsection="saveas/xlsx-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将XLSX文件另存为PHP中的MD" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLSX 中的文件格式保存为 MD 是一项复杂的任务。所有 XLSX 到 MD 格式的转换均由我们的 PHP SDK 执行，同时保留源 XLSX 电子表格的主要结构和逻辑内容。我们的 PHP 库是在线将 XLSX 保存为 MD 文件的专业解决方案。该Cloud SDK为PHP开发者提供了强大的功能和完美的MD输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP 使用 REST 将 XLSX 保存为 MD 的代码示例 API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xlsx';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "md";
    $newfilename = "Book1Saveas.md";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells云SDK for PHP将Excel文件保存为其他格式XLSX为MD" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `PostWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
