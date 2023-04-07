﻿---
title: 将 TSV 保存为 TIFF API 为 Python
description: 用于 Microsoft Excel 和 OpenOffice Calc 的云 API 和 SDK。将电子表格转换为其他格式文件。
url: /zh/python/saveas/tsv-to-tiff/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API 将 TSV 保存为 TIFF" h2="Python 库将 TSV 另存为 TIFF" p="使用 Cells SaveAs REST API 在 Python 创建自定义电子表格工作流程。这是使用 Python 在线将 TSV 保存为 TIFF 和其他文档格式的专业解决方案。" urlsection="saveas/tsv-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Python 中保存一个 TSV 文件为 TIFF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 TSV 中的文件格式保存为 TIFF 是一项复杂的任务。所有 TSV 到 TIFF 格式的转换都由我们的 Python SDK 执行，同时保持源 TSV 电子表格的主要结构和逻辑内容。我们的 Python 库是将 TSV 在线保存为 TIFF 文件的专业解决方案。此 Cloud SDK 为 Python 开发人员提供了强大的功能和完美的 TIFF 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python 中的代码示例使用 REST API 将 TSV 保存为 TIFF 格式" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.tsv'    
    saveOptions = None
    newfilename = "Book1Saveas.tiff"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Python API将TSV另存为TIFF" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获得免费的 API 配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>通话单元_节省_作为_邮政_文档_节省_作为获取结果流的方法</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Python 2.7 或更新版本</li>
<li>Python 3.10 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}