---
title: 使用 Python 将 XLTX 保存为 MHTML
description: 利用Aspose.Cells Cloud SDK for Python将XLTX格式文件保存为MHTML格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 XLTX 保存为 MHTML" h2="Python 用于将 XLTX 保存为 MHTML 的库" p="使用Cells云的SaveAs API在Python中创建自定义电子表格工作流程。这是使用Python在线将XLTX保存为MHTML和其他文档格式的专业解决方案。" urlsection="saveas/xltx-to-mhtml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Python 中将 XLTX 文件另存为 MHTML" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLTX 中的文件格式保存为 MHTML 是一项复杂的任务。所有 XLTX 到 MHTML 格式的转换均由我们的 Python SDK 执行，同时保留源 XLTX 电子表格的主要结构和逻辑内容。我们的 Python 库是在线将 XLTX 保存为 MHTML 文件的专业解决方案。该Cloud SDK为Python开发人员提供了强大的功能和完美的MHTML输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python 使用 REST 将 XLTX 保存为 MHTML 的代码示例 API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xltx'    
    saveOptions = None
    newfilename = "Book1Saveas.mhtml"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Python将Excel文件保存为其他格式XLTX为MHTML" >}}
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
