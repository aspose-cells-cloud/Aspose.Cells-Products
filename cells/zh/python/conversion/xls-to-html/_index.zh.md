---
title: 使用 Python 将 XLS 转换为 HTML
description: 利用Aspose.Cells Cloud SDK for Python将XLS格式文件转换为HTML格式文件。
kwords: Excel, Convert XLS to HTML, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLS to HTML using the Cells Cloud Python library.","description": "How to convert XLS to HTML using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/conversion/xls-to-html/","step": [{ "@type": "HowToStep","name": "How to convert XLS to HTML using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/xls-to-html/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLS to HTML using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/xls-to-html/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLS to HTML using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/xls-to-html/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to convert XLS to HTML using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/xls-to-html/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLS 转换为 HTML" h2="Python 用于将 XLS 转换为 HTML 的库" p="使用 Cells 云的转换 API 在 Python 项目中创建自定义电子表格工作流程。这是使用Python在线将XLS转换为HTML和其他文档格式的专业解决方案。" urlsection="conversion/xls-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Python 将 XLS 转换为 HTML" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLS 转换为 HTML 可能是一项复杂的任务。我们的 Python SDK 可处理所有 XLS 到 HTML 格式的转换，同时保留源 XLS 电子表格的主要结构和逻辑内容。我们的 Python 库提供了将 XLS 在线转换为 HTML 文件的专业解决方案。此 Cloud SDK 为 Python 开发人员提供了强大的功能，并确保了高质量的 HTML 输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python 使用 Cells Cloud SDK 将 XLS 转换为 HTML 的代码示例" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xls",format="html")
    shutil.move(file1, "destFile.html")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells 云 Python 库将 XLS 转换为 HTML。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Python 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Python中的源文件。</li>
<li>使用 `put_convert_workbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Python 2.7 或更新版本</li>
<li>Python 3.10 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
