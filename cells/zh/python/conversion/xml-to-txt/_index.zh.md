---
title: 使用 Python 将 XML 转换为 TXT
description: 利用Aspose.Cells Cloud SDK for Python将XML格式文件转换为TXT格式文件。
kwords: Excel, Convert XML to TXT, REST, Python
howto: How to convert XML to TXT using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XML 转换为 TXT" h2="Python 用于将 XML 转换为 TXT 的库" p="使用 Cells 云的转换 API 在 Python 项目中创建自定义电子表格工作流程。这是使用Python在线将XML转换为TXT和其他文档格式的专业解决方案。" urlsection="conversion/xml-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Python 将 XML 转换为 TXT" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XML 转换为 TXT 可能是一项复杂的任务。我们的 Python SDK 处理所有 XML 到 TXT 格式的转换，同时保留源 XML 电子表格的主要结构和逻辑内容。我们的 Python 库提供了在线将 XML 转换为 TXT 文件的专业解决方案。该Cloud SDK为Python开发者提供强大的功能，并保证高质量的TXT输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python 使用 Cells Cloud SDK 将 XML 转换为 TXT 的代码示例" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xml",format="txt")
    shutil.move(file1, "destFile.txt")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Python 库将 XML 转换为 TXT。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Python 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Python中的源文件。</li>
<li>使用 `put_convert_workbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Python 2.7 或更高版本</li>
<li>Python 3.10 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
