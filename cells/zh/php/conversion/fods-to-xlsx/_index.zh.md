---
title: 在云端将 FODS 转换为 XLSX via PHP
description: 使用 REST API 和开源 PHP SDK 创建、编辑或转换 Excel 文件
url: /zh/php/conversion/fods-to-xlsx/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: XLSX
platform: PHP
otherformats: SVG MHTML XLTM XLTX XLSB XLSM DIF XLSX TXT PDF ODS TSV CSV XML XPS FODS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="使用 PHP 将 FODS 转换为 XLSX" h2="使用适用于 PHP 的开源 Cloud SDK 自动执行 Excel 和 OpenOffice 文件转换" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="快速将 FODS 转换为 XLSX via PHP" %}}
1. 创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息
1. 使用客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 ```CellsApi```
1. 使用 ```CellsApi.uploadFile``` 方法将 FODS 文件上传到默认云存储
1. 致电 ```CellsApi.cellsSaveAsPostDocumentSaveAs``` 获取生成的 XLSX 文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="开始使用 Excel API 和 PHP SDK" %}}
获取 Excel Cloud SDK for PHP 源代码[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php)自己编译 SDK 或前往[发布](https://releases.aspose.cloud/)以获得替代下载选项。

另请查看基于 Swagger 的[API 参考](https://apireference.aspose.cloud/cells/)了解更多关于[Excel 休息 API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP FODS 到 XLSX 转换代码" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.xlsx";
$isAutoFitRows= 'true';
$isAutoFitColumns= 'true';
$folder = "Temp";
CellsApi::ready( $this->instance, $name, $folder );
$result = $this->instance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename, $isAutoFitRows, $isAutoFitColumns, $folder);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}