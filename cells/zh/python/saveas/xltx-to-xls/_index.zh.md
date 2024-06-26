---
title: 使用 Python 将 XLTX 保存为 XLS
description: 利用Aspose.Cells Cloud SDK for Python将XLTX格式文件保存为XLS格式文件。
kwords: Excel, Save XLTX as XLS, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLTX as XLS using the Cells Cloud Python library.","description": "How to save XLTX as XLS using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/saveas/xltx-to-xls/","step": [{ "@type": "HowToStep","name": "How to save XLTX as XLS using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xltx-to-xls/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLTX as XLS using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xltx-to-xls/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLTX as XLS using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xltx-to-xls/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to save XLTX as XLS using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xltx-to-xls/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLTX 保存为 XLS" h2="Python 用于将 XLTX 保存为 XLS 的库" p="使用Cells云的SaveAs API在Python中创建自定义电子表格工作流程。这是使用Python在线将XLTX保存为XLS和其他文档格式的专业解决方案。" urlsection="saveas/xltx-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section title="将 XLTX 文件另存为 Python 中的 XLS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将文件格式从 XLTX 保存为 XLS 是一项复杂的任务。所有 XLTX 到 XLS 格式的转换均由我们的 Python SDK 执行，同时保留源 XLTX 电子表格的主要结构和逻辑内容。我们的 Python 库是在线将 XLTX 保存为 XLS 文件的专业解决方案。该Cloud SDK为Python开发人员提供了强大的功能和完美的XLS输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python 使用 REST 将 XLTX 保存为 XLS 的代码示例 API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xltx'    
    saveOptions = None
    newfilename = "Book1Saveas.xls"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells 云 Python 库将 XLTX 保存为 XLS。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Python 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Python中的源文件。</li>
<li>使用 `post_workbook_save_as` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Python 2.7 或更新版本</li>
<li>Python 3.10 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
