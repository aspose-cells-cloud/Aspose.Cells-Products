---
title: 使用 Python 将 XLSX 保存为 TIFF
description: 利用Aspose.Cells Cloud SDK for Python将XLSX格式文件保存为TIFF格式文件。
kwords: Excel, Save XLSX as TIFF, REST, Python
howto: How to save XLSX as TIFF using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将XLSX另存为TIFF" h2="Python 用于将 XLSX 保存为 TIFF 的库" p="使用Cells云的SaveAs API在Python中创建自定义电子表格工作流程。这是使用Python在线将XLSX另存为TIFF和其他文档格式的专业解决方案。" urlsection="saveas/xlsx-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="将 XLSX 文件另存为 Python 中的 TIFF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLSX 中的文件格式保存为 TIFF 是一项复杂的任务。所有 XLSX 到 TIFF 格式的转换均由我们的 Python SDK 执行，同时保留源 XLSX 电子表格的主要结构和逻辑内容。我们的 Python 库是在线将 XLSX 保存为 TIFF 文件的专业解决方案。此Cloud SDK为Python开发者提供了强大的功能和完美的TIFF输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python 使用 REST 将 XLSX 保存为 TIFF 的代码示例 API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlsx'    
    saveOptions = None
    newfilename = "Book1Saveas.tiff"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Python 库将 XLSX 另存为 TIFF。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Python 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Python中的源文件。</li>
<li>使用 `post_workbook_save_as` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Python 2.7 或更高版本</li>
<li>Python 3.10 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
