﻿---
title:  CSV 到 PDF 将 API 转换为 PHP
description: 用于 Microsoft Excel 和 OpenOffice Calc 的云 API 和 SDK。将电子表格转换为其他格式文件。
url: /zh/php/conversion/csv-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API 将 CSV 转换为 PDF" h2="PHP 将 CSV 转换为 PDF 的库" p="使用 Cells Conversion REST API 在 PHP 中创建自定义电子表格工作流。这是一个使用 PHP 在线将 CSV 转换为 PDF 和其他文档格式的专业解决方案。" urlsection="conversion/csv-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 CSV 文件转换为 PHP 中的 PDF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 CSV 转换为 PDF 是一项复杂的任务。所有 CSV 到 PDF 格式的转换都由我们的 PHP SDK 执行，同时保持源 CSV 电子表格的主要结构和逻辑内容。我们的 PHP 库是将 CSV 在线转换为 PDF 文件的专业解决方案。此 Cloud SDK 为 PHP 开发人员提供了强大的功能和完美的 PDF 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP 中的代码示例使用 REST API 将 CSV 转换为 PDF 格式" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.csv';    
    $format ='pdf';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.pdf", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用PHP API将CSV转换为PDF" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获得免费的 API 配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 cellsWorkbookPutConvertWorkBook 方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}