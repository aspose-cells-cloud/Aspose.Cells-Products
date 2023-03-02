---
title: 从 Excel FODS 转换为 XLTM via Python
description: 使用 REST API 和开源 Python SDK 创建、编辑或转换 Excel 文件
url: /zh/python/conversion/fods-to-xltm/
family: cells
platformtag: python
feature: conversion
informat: FODS
outformat: XLTM
platform: Python
otherformats: TSV DIF XLSB XML XLSX MHTML FODS MD XPS CSV XLSM XLTM XLTX TIFF PDF TXT 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="使用 Python 将 FODS 转换为 XLTM" h2="使用 Python 的开源 Cloud SDK 读取、编辑和导出 Excel 数据为其他格式" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="使用 Python 将 FODS 转换为 XLTM" %}}
1. 创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获得免费的 API 配额和授权详细信息
1. 使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 ```CellsApi```
1. 使用 ```CellsApi.upload_file``` 方法将 FODS 文件上传到默认云存储
1. 调用```CellsApi.cells_save_as_post_document_save_as```方法得到生成的XLTM文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="开始使用 Excel API & Python SDK" %}}
从 Python 源代码中获取 Excel Cloud SDK[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python)自己编译 SDK 或前往[发布](https://releases.aspose.cloud/)替代下载选项。

也可以看看基于 Swagger 的[API 参考](https://apireference.aspose.cloud/cells/)了解更多[Excel 休息 API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Python FODS 到 XLTM 转换代码" gistPath="" %}}
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python
import os
import sys
import asposecellscloud
from asposecellscloud.apis.cells_api import CellsApi
api  = asposecellscloud.apis.cells_api.CellsApi(os.getenv('CellsCloudClientId'), os.getenv('CellsCloudClientSecret'), "v3.0" ,os.getenv('CellsCloudApiBaseUrl'))

name ='template.fods'    
saveOptions = None
newfilename = "output.xltm"
isAutoFitRows= True
isAutoFitColumns= True
folder = "temp"
result = api.upload_file(folder + '/' + name,  "c:/TestData/" + name)
 
result = api.cells_save_as_post_document_save_as(name, save_options=saveOptions, newfilename=(folder +'/' + newfilename), is_auto_fit_rows=isAutoFitRows, is_auto_fit_columns=isAutoFitColumns, folder=folder)
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}