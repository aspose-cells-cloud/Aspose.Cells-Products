---
title: 将 XLSM 保存为 SQL API 为 PHP
description: 使用Aspose.Cells Cloud SDK for PHP将XLSM格式文件保存为SQL格式文件。
url: /zh/php/saveas/xlsm-to-sql/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API 将 XLSM 保存为 SQL" h2="PHP 将 XLSM 保存为 SQL 的库" p="使用 Cells SaveAs REST API 在 PHP 中创建自定义电子表格工作流程。这是使用 PHP 在线将 XLSM 保存为 SQL 和其他文档格式的专业解决方案。" urlsection="saveas/xlsm-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 XLSM 文件另存为 PHP 中的 SQL" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLSM 中的文件格式保存为 SQL 是一项复杂的任务。所有 XLSM 到 SQL 格式的转换均由我们的 PHP SDK 执行，同时保留源 XLSM 电子表格的主要结构和逻辑内容。我们的 PHP 库是在线将 XLSM 保存为 SQL 文件的专业解决方案。此Cloud SDK为PHP开发者提供了强大的功能和完美的SQL输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP 中的代码示例使用 REST API 将 XLSM 保存为 SQL 格式" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xlsm';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "sql";
    $newfilename = "Book1Saveas.sql";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用PHP API将XLSM保存为SQL" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 cellsSaveAsPostDocumentSaveAs 方法来获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
