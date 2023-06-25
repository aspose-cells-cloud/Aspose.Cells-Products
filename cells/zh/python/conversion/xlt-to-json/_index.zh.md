---
title: XLT 到 JSON 将 API 转换为 Python
description: 使用Aspose.Cells Cloud SDK for Python将XLT格式文件转换为JSON格式文件。
url: /zh/python/conversion/xlt-to-json/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API 将 XLT 转换为 JSON" h2="Python 将 XLT 转换为 JSON 的库" p="使用 Cells Conversion REST API 在 Python 中创建自定义电子表格工作流程。这是使用 Python 在线将 XLT 转换为 JSON 和其他文档格式的专业解决方案。" urlsection="conversion/xlt-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 XLT 文件转换为 Python 中的 JSON" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLT 转换为 JSON 是一项复杂的任务。所有 XLT 到 JSON 格式的转换均由我们的 Python SDK 执行，同时保留源 XLT 电子表格的主要结构和逻辑内容。我们的 Python 库是在线将 XLT 转换为 JSON 文件的专业解决方案。该Cloud SDK为Python开发者提供了强大的功能和完美的JSON输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python 中的代码示例使用 REST API 将 XLT 转换为 JSON 格式" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlt",format="json")
    shutil.move(file1, "destFile.json")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Python API 将 XLT 转换为 JSON" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>呼叫细胞_作业簿_放_转变_获取结果流的工作簿方法</li>
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
