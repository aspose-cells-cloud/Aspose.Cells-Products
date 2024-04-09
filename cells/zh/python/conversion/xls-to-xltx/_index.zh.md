---
title: 使用 Python 将 XLS 转换为 XLTX
description: 利用Python的Aspose.Cells Cloud SDK将XLS格式文件转换为XLTX格式文件。
kwords: Excel, Convert XLS to XLTX, REST, Python
howto: How to convert XLS to XLTX using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLS 转换为 XLTX" h2="Python 用于将 XLS 转换为 XLTX 的库" p="使用 Cells 云的转换 API 在 Python 项目中创建自定义电子表格工作流程。这是使用 Python 在线将 XLS 转换为 XLTX 和其他文档格式的专业解决方案。" urlsection="conversion/xls-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Python 将 XLS 转换为 XLTX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLS 转换为 XLTX 可能是一项复杂的任务。我们的 Python SDK 处理所有 XLS 到 XLTX 格式的转换，同时保留源 XLS 电子表格的主要结构和逻辑内容。我们的 Python 库提供了在线将 XLS 转换为 XLTX 文件的专业解决方案。该Cloud SDK为Python开发者提供了强大的功能，并确保高质量的XLTX输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python 使用 Cells Cloud SDK 将 XLS 转换为 XLTX 的代码示例" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xls",format="xltx")
    shutil.move(file1, "destFile.xltx")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Python 库将 XLS 转换为 XLTX。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Python 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Python中的源文件。</li>
<li>使用 `put_convert_workbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Python 2.7 或更高版本</li>
<li>Python 3.10 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
