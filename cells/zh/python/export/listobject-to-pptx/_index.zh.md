---
title: 使用 Cells Cloud SDK for Python 将 LISTOBJECT 从 Excel 导出到 PPTX
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 LISTOBJECT 从 Excel 导出到 PPTX" h2="Python 用于将 LISTOBJECT 导出到 PPTX 文件的库" p="使用Cells云的导出API导出Python中的Excel文件内部对象工作流程。这是使用Python在线电子表格将LISTOBJECT导出为PPTX格式文件的专业解决方案。" urlsection="export/listobject-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="使用 Cells Cloud SDK for Python 将 LISTOBJECT 对象导出为 PPTX 格式文件" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 LISTOBJECT 对象从 Excel 文件导出到 PPTX 文件是一项复杂的任务。将 LISTOBJECT 导出到 PPTX 格式转换由我们的 Python SDK 执行，同时保留源 LISTOBJECT 电子表格的主要结构和逻辑内容。我们的 Python 库是在线将 LISTOBJECT 对象导出为 PPTX 格式文件的专业解决方案。该Cloud SDK为Python开发者提供了强大的功能和完美的PPTX输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python 中的代码示例使用 REST API 将 LISTOBJECT 从电子表格导出为 PPTX 格式" gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"listobject","pptx")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Python的Cells Cloud SDK将Excel LISTOBJECT中的对象导出到PPTX" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>调用post_export方法获取结果流</li>
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
