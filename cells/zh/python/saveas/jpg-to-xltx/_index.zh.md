---
title: 使用 Python 将 JPG 保存为 XLTX
description: 利用Aspose.Cells Cloud SDK for Python将JPG格式文件保存为XLTX格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 JPG 保存为 XLTX" h2="Python 用于将 JPG 保存为 XLTX 的库" p="使用Cells云的SaveAs API在Python中创建自定义电子表格工作流程。这是使用Python在线将JPG保存为XLTX和其他文档格式的专业解决方案。" urlsection="saveas/jpg-to-xltx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 JPG 文件另存为 XLTX 中的 Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 JPG 文件格式保存为 XLTX 是一项复杂的任务。所有 JPG 到 XLTX 格式的转换均由我们的 Python SDK 执行，同时保留源 JPG 电子表格的主要结构和逻辑内容。我们的 Python 库是在线将 JPG 保存为 XLTX 文件的专业解决方案。该Cloud SDK为Python开发者提供了强大的功能和完美的XLTX输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python 使用 REST 将 JPG 保存为 XLTX 的代码示例 API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.jpg'    
    saveOptions = None
    newfilename = "Book1Saveas.xltx"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells云SDK for Python将Excel文件保存为其他格式JPG为XLTX" >}}
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
