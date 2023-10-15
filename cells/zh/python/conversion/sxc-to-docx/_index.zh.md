---
title: 使用 Python 将 SXC 转换为 DOCX
description: 利用Python的Aspose.Cells Cloud SDK将SXC格式文件转换为DOCX格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 SXC 转换为 DOCX" h2="Python 用于将 SXC 转换为 DOCX 的库" p="使用 Cells 云的转换 API 在 Python 项目中创建自定义电子表格工作流程。这是使用Python在线将SXC转换为DOCX和其他文档格式的专业解决方案。" urlsection="conversion/sxc-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="使用 Cells Cloud SDK for Python 将 SXC 转换为 DOCX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 SXC 转换为 DOCX 可能是一项复杂的任务。我们的 Python SDK 处理所有 SXC 到 DOCX 格式的转换，同时保留源 SXC 电子表格的主要结构和逻辑内容。我们的 Python 库提供了在线将 SXC 转换为 DOCX 文件的专业解决方案。该Cloud SDK为Python开发者提供强大的功能，并保证高质量的DOCX输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python 使用 Cells Cloud SDK 将 SXC 转换为 DOCX 的代码示例" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.sxc",format="docx")
    shutil.move(file1, "destFile.docx")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Python将Excel文件转换为其他格式SXC转DOCX" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `put_convert_workbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Python 2.7 或更高版本</li>
<li>Python 3.10 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
