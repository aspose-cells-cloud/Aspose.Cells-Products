---
title: 使用 Python 将 CSV 保存为 XLSB
description: 利用Aspose.Cells Cloud SDK for Python将CSV格式文件保存为XLSB格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 CSV 保存为 XLSB" h2="Python 用于将 CSV 保存为 XLSB 的库" p="使用Cells云的SaveAs API在Python中创建自定义电子表格工作流程。这是使用Python在线将CSV保存为XLSB和其他文档格式的专业解决方案。" urlsection="saveas/csv-to-xlsb/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 CSV 文件另存为 XLSB，位于 Python 中" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 CSV 文件格式保存为 XLSB 是一项复杂的任务。所有 CSV 到 XLSB 格式的转换均由我们的 Python SDK 执行，同时保留源 CSV 电子表格的主要结构和逻辑内容。我们的 Python 库是在线将 CSV 保存为 XLSB 文件的专业解决方案。该Cloud SDK为Python开发人员提供了强大的功能和完美的XLSB输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python 使用 REST 将 CSV 保存为 XLSB 的代码示例 API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.csv'    
    saveOptions = None
    newfilename = "Book1Saveas.xlsb"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Python将Excel文件保存为其他格式CSV为XLSB" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `post_workbook_save_as` 方法检索结果流。</li>
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
