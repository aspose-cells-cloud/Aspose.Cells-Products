---
title: 使用 Cells Cloud SDK for Go 将 LISTOBJECT 从 Excel 导出到 HTML
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
kwords: Excel, listobject, html, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Go to export objects from Excel LISTOBJECT to HTML","description": "How to use Cells Cloud SDK for Go to export objects from Excel LISTOBJECT to HTML","image": {"@type": "ImageObject"},"url": "/go/export/listobject-to-html/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel LISTOBJECT to HTML step 1", "image": {"@type": "ImageObject",},"url": "/go/export/listobject-to-html/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel LISTOBJECT to HTML step 1", "image": {"@type": "ImageObject",},"url": "/go/export/listobject-to-html/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel LISTOBJECT to HTML step 1", "image": {"@type": "ImageObject",},"url": "/go/export/listobject-to-html/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 LISTOBJECT 从 Excel 导出到 HTML" h2="用于将 LISTOBJECT 导出到 HTML 文件的 Go 库" p="使用Cells云的Export API导出Go中的Excel文件内部对象工作流程。这是使用 Go 在线电子表格将 LISTOBJECT 导出为 HTML 格式文件的专业解决方案。" urlsection="export/listobject-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Go 将 LISTOBJECT 对象导出为 HTML 格式文件" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 LISTOBJECT 对象从 Excel 文件导出到 HTML 文件是一项复杂的任务。将 LISTOBJECT 导出到 HTML 格式转换由我们的 Go SDK 执行，同时保留源 LISTOBJECT 电子表格的主要结构和逻辑内容。我们的 Go 库是在线将 LISTOBJECT 对象导出为 HTML 格式文件的专业解决方案。这个Cloud SDK为Go开发者提供了强大的功能和完美的HTML输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go 中使用 REST API 将 LISTOBJECT 从电子表格导出为 HTML 格式的代码示例" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "encoding/base64"
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewLightCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    var files map[string]string
	    files = make(map[string]string)
	    files["Book1.xlsx"] = "C:/Book1.xlsx"
	    files["myDocument.xlsx"] = "C:/myDocument.xlsx"
	    postExportOpts := new(asposecellscloud.PostExportOpts)
	    postExportOpts.ObjectType = "listobject"
	    postExportOpts.Format = "html"
	    filesresult, _, err := instance.PostExport(files, postExportOpts)
	    if err != nil {
		    return
	    }
	    print(filesresult.Files[0].Filename)
	    originalStringBytes, err1 := base64.StdEncoding.DecodeString(filesresult.Files[0].FileContent)
	    if err1 != nil {
		    return
	    }
	    f, err2 := os.Create(filesresult.Files[0].Filename)
	    if err2 != nil {
		    return
	    }
	    _, err3 := f.Write(originalStringBytes)
	    if err3 != nil {
		    return
	    }
	    f.Close()
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells Cloud SDK for Go 将 Excel LISTOBJECT 中的对象导出到 HTML" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `postExport` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>go 版本 go1.13.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
