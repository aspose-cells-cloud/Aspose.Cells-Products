---
title: 使用 Cells Cloud SDK for Python 将 WORKBOOK 从 Excel 导出到 PNG
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
kwords: Excel, workbook, png, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to PNG","description": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to PNG","image": {"@type": "ImageObject"},"url": "/python/export/workbook-to-png/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to PNG step 1", "image": {"@type": "ImageObject",},"url": "/python/export/workbook-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to PNG step 1", "image": {"@type": "ImageObject",},"url": "/python/export/workbook-to-png/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Python to export objects from Excel WORKBOOK to PNG step 1", "image": {"@type": "ImageObject",},"url": "/python/export/workbook-to-png/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将工作簿从 Excel 导出到 PNG" h2="Python 库用于将 WORKBOOK 导出到 PNG 文件" p="使用 Cells 云的导出 API 导出 Python 中的 Excel 文件内部对象工作流。这是一个专业的解决方案，可使用 Python 在线将电子表格中的 WORKBOOK 导出为 PNG 格式的文件。" urlsection="export/workbook-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Python 将 WORKBOOK 对象导出为 PNG 格式文件" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 WORKBOOK 对象从 Excel 文件导出到 PNG 文件是一项复杂的任务。将 WORKBOOK 导出到 PNG 格式的转换由我们的 Python SDK 执行，同时保留源 WORKBOOK 电子表格的主要结构和逻辑内容。我们的 Python 库是一个专业的解决方案，可在线将 WORKBOOK 对象导出到 PNG 格式的文件。此云 SDK 为 Python 开发人员提供了强大的功能和完美的 PNG 输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python 中的代码示例使用 REST API 将电子表格中的 WORKBOOK 导出为 PNG 格式" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import base64
    from asposecellscloud.apis.light_cells_api import LightCellsApi
    cells_api = LightCellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    files ={ 
        "myDocument.xlsx" :  "c:/myDocument.xlsx",
        "Book1.xlsx" :  "c:/Book1.xlsx" 
        }
    result = cells_api.post_export(files ,"workbook","png")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Python将对象从Excel WORKBOOK导出到PNG" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>调用post_export方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Python 2.7 或更新版本</li>
<li>Python 3.10 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
