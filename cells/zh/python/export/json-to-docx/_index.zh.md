---
title: 导出Json到DOCX文件via Python
description: Aspose.Cells Cloud REST API 支持将 Excel 文件和内部对象导出为各种格式文件。 SDK支持多种开发语言。它们包括 Android、C#、Go、Java、NodeJS、Perl、PHP、Python、Ruby 和 swift。
url: /zh/python/export/json-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="在云端将 JSON 导出为 DOCX 文件" h2="Excel & 使用开源 Cloud SDK 导出 OpenOffice 电子表格 Python" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="在 Cloud SDK 中将 JSON 导出为 DOCX 文件 Python" %}}
1. 创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息
1. 使用客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 ```CellsApi```
1. 调用```cells_workbook_put_convert_workbook```方法获取生成的DOCX流
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="开始使用 Excel REST API" %}}
获取 Excel Cloud SDK for .NET 源代码[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python)自己编译 SDK 或前往[发布](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/releases)以获得替代下载选项。

另请查看基于 Swagger 的[API 参考]()了解更多关于[Excel 休息 API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Python JSON 到 DOCX 转换的代码" gistPath="" %}}
```python
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlsx",format="docx")
    shutil.move(file1, "destFile.docx")     
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
