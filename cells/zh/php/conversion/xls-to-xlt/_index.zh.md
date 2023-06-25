---
title:  XLS 到 XLT 将 API 转换为 PHP
description: 使用Aspose.Cells Cloud SDK for PHP将XLS格式文件转换为XLT格式文件。
url: /zh/php/conversion/xls-to-xlt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API 将 XLS 转换为 XLT" h2="PHP 将 XLS 转换为 XLT 的库" p="使用Cells转换REST API在PHP中创建自定义电子表格工作流程。这是使用PHP在线将XLS转换为XLT和其他文档格式的专业解决方案。" urlsection="conversion/xls-to-xlt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 XLS 文件转换为 PHP 中的 XLT" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLS 转换为 XLT 是一项复杂的任务。所有 XLS 到 XLT 格式的转换均由我们的 PHP SDK 执行，同时保留源 XLS 电子表格的主要结构和逻辑内容。我们的 PHP 库是在线将 XLS 转换为 XLT 文件的专业解决方案。该Cloud SDK为PHP开发人员提供了强大的功能和完美的XLT输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP 中的代码示例使用 REST API 将 XLS 转换为 XLT 格式" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xls';    
    $format ='xlt';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xlt", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 PHP API 将 XLS 转换为 XLT" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 cellsWorkbookPutConvertWorkBook 方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
