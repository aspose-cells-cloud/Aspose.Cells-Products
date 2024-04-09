---
title: 使用 Cells Cloud SDK for PHP 将 CHART 从 Excel 导出为 WMF
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="将 CHART 从 Excel 导出到 WMF" h2="PHP 用于将图表导出为 WMF 文件的库" p="使用Cells云的导出API导出PHP中的Excel文件内部对象工作流程。这是使用PHP在线将电子表格中的CHART导出为WMF格式文件的专业解决方案。" urlsection="export/chart-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用Cells Cloud SDK for PHP将CHART对象导出为WMF格式文件" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 CHART 对象从 Excel 文件导出到 WMF 文件是一项复杂的任务。将 CHART 导出为 WMF 格式转换由我们的 PHP SDK 执行，同时保留源 CHART 电子表格的主要结构和逻辑内容。我们的 PHP 库是在线将 CHART 对象导出为 WMF 格式文件的专业解决方案。该Cloud SDK为PHP开发人员提供了强大的功能和完美的WMF输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP 中的代码示例使用 REST API 将电子表格中的 CHART 导出为 WMF 格式" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\LightCellsApi;
    $cells = new LightCellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $files = array (
        'DataSource' =>  "C:/datasource.xlsx",
        'AssemblyTest' => "C:/assemblytest.xlsx"
    );
    $result = $cells->postExport( $files,'chart', 'wmf' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 PHP 的 Cells Cloud SDK 将对象从 Excel CHART 导出到 WMF" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `postExport` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>PHP 7.4 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
