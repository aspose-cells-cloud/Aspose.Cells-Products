---
title: 使用 PHP 将 XLSM 转换为 DOCX
description: 利用Aspose.Cells Cloud SDK for PHP将XLSM格式文件转换为DOCX格式文件。
kwords: Excel, Convert XLSM to DOCX, REST, PHP
howto: How to convert XLSM to DOCX using Aspose.Cells Cloud PHP library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLSM 转换为 DOCX" h2="PHP 用于将 XLSM 转换为 DOCX 的库" p="使用 Cells 云的转换 API 在 PHP 项目中创建自定义电子表格工作流程。这是使用 PHP 在线将 XLSM 转换为 DOCX 和其他文档格式的专业解决方案。" urlsection="conversion/xlsm-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for PHP 将 XLSM 转换为 DOCX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLSM 转换为 DOCX 可能是一项复杂的任务。我们的 PHP SDK 处理所有 XLSM 到 DOCX 格式的转换，同时保留源 XLSM 电子表格的主要结构和逻辑内容。我们的 PHP 库提供了在线将 XLSM 转换为 DOCX 文件的专业解决方案。该Cloud SDK为PHP开发者提供强大的功能，并保证高质量的DOCX输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP 使用 Cells Cloud SDK 将 XLSM 转换为 DOCX 的代码示例" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xlsm';    
    $format ='docx';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.docx", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud PHP 库将 XLSM 转换为 DOCX。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 PHP 库并将引用（导入库）添加到您的项目中。</li>
<li>打开PHP中的源文件。</li>
<li>使用 `putConvertWorkbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
