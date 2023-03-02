---
title: 将 Ods 导出到 XLSX 文件 via PHP
description: Aspose.Cells Cloud REST API 支持将 Excel 文件和内部对象导出为各种格式文件。 SDK支持多种开发语言。它们包括 Android、C#、Go、Java、NodeJS、Perl、PHP、Python、Ruby 和 swift。
url: /zh/php/export/ods-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="将 ODS 导出到云端的 XLSX 文件" h2="Excel 和 PHP 的开源 Cloud SDK 的 OpenOffice 电子表格导出" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="在 Cloud SDK 中将 ODS 导出到 XLSX 文件，用于 PHP" %}}
1. 创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获得免费的 API 配额和授权详细信息
1. 使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 ```CellsApi```
1. 调用 ```cellsWorkbookPutConvertWorkBook``` 方法获取生成的 XLSX 流
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="开始使用 Excel REST API" %}}
获取Excel Cloud SDK for .NET源码[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php)自己编译 SDK 或前往[发布](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/releases)替代下载选项。

也可以看看基于 Swagger 的[API 参考]()了解更多[Excel 休息 API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP ODS 到 XLSX 转换的代码" gistPath="" %}}
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xlsx';    
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

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
