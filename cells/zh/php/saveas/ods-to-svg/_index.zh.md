﻿---
title: 将 ODS 保存为 SVG API 为 PHP
description: 用于 Microsoft Excel 和 OpenOffice Calc 的云 API 和 SDK。将电子表格转换为其他格式文件。
url: /zh/php/saveas/ods-to-svg/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API 将ODS保存为SVG" h2="PHP库保存ODS为SVG" p="使用Cells SaveAs REST API在PHP中创建自定义电子表格工作流。这是使用PHP在线将ODS保存为SVG和其他文档格式的专业解决方案。" urlsection="saveas/ods-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在PHP中保存一个ODS文件为SVG" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 ODS 中的文件格式保存为 SVG 是一项复杂的任务。所有 ODS 到 SVG 格式的转换都由我们的 PHP SDK 执行，同时保持源 ODS 电子表格的主要结构和逻辑内容。我们的 PHP 库是将 ODS 在线保存为 SVG 文件的专业解决方案。此 Cloud SDK 为 PHP 开发人员提供了强大的功能和完美的 SVG 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP中的代码示例使用REST API将ODS保存为SVG格式" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.ods';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "svg";
    $newfilename = "Book1Saveas.svg";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用PHP API将ODS另存为SVG" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获得免费的 API 配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 cellsSaveAsPostDocumentSaveAs 方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}