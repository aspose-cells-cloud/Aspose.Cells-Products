---
title: 使用 PHP 将 XLTX 转换为 EMF
description: 利用Aspose.Cells Cloud SDK for PHP将XLTX格式文件转换为EMF格式文件。
kwords: Excel, Convert XLTX to EMF, REST, PHP
howto: How to convert XLTX to EMF using Aspose.Cells Cloud PHP library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLTX 转换为 EMF" h2="PHP 用于将 XLTX 转换为 EMF 的库" p="使用 Cells 云的转换 API 在 PHP 项目中创建自定义电子表格工作流程。这是使用PHP在线将XLTX转换为EMF和其他文档格式的专业解决方案。" urlsection="conversion/xltx-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for PHP 将 XLTX 转换为 EMF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLTX 转换为 EMF 可能是一项复杂的任务。我们的 PHP SDK 处理所有 XLTX 到 EMF 格式转换，同时保留源 XLTX 电子表格的主要结构和逻辑内容。我们的 PHP 库提供了在线将 XLTX 转换为 EMF 文件的专业解决方案。该Cloud SDK为PHP开发者提供了强大的功能，并保证了EMF的高质量输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP 使用 Cells Cloud SDK 将 XLTX 转换为 EMF 的代码示例" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xltx';    
    $format ='emf';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.emf", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells 云 PHP 库将 XLTX 转换为 EMF。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 PHP 库并将引用（导入库）添加到您的项目中。</li>
<li>打开PHP中的源文件。</li>
<li>使用 `putConvertWorkbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
