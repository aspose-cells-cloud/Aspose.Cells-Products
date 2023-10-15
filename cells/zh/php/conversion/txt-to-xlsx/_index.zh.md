---
title: 使用 PHP 将 TXT 转换为 XLSX
description: 利用PHP的Aspose.Cells Cloud SDK将TXT格式文件转换为XLSX格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 TXT 转换为 XLSX" h2="PHP 用于将 TXT 转换为 XLSX 的库" p="使用 Cells 云的转换 API 在 PHP 项目中创建自定义电子表格工作流程。这是使用PHP在线将TXT转换为XLSX和其他文档格式的专业解决方案。" urlsection="conversion/txt-to-xlsx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="使用 Cells Cloud SDK for PHP 将 TXT 转换为 XLSX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 TXT 转换为 XLSX 可能是一项复杂的任务。我们的 PHP SDK 处理所有 TXT 到 XLSX 格式的转换，同时保留源 TXT 电子表格的主要结构和逻辑内容。我们的 PHP 库提供了在线将 TXT 转换为 XLSX 文件的专业解决方案。该Cloud SDK为PHP开发者提供了强大的功能，并确保高质量的XLSX输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP 使用 Cells Cloud SDK 将 TXT 转换为 XLSX 的代码示例" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.txt';    
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
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells云SDK for PHP将Excel文件转换为其他格式TXT转XLSX" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `putConvertWorkbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
