---
title: 使用 Go 将 HTML 转换为 DIF
description: 利用Aspose.Cells Cloud SDK for Go将HTML格式文件转换为DIF格式文件。
kwords: Excel, Convert HTML to DIF, REST, Go
howto: "{"@context": "https://schema.org","@type": "HowTo","name": "How to convert HTML to DIF using the Cells Cloud Go library.","description": "How to convert HTML to DIF using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/conversion/html-to-dif/","step": [{ "@type": "HowToStep","name": "How to convert HTML to DIF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/html-to-dif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert HTML to DIF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/html-to-dif/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert HTML to DIF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/html-to-dif/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to convert HTML to DIF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/html-to-dif/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}"
fqa: "{"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}"
---
{{< blocks/products/cells/cells-cloud-banner h1="将 HTML 转换为 DIF" h2="用于将 HTML 转换为 DIF 的 Go 库" p="使用 Cells 云的转换 API 在 Go 项目中创建自定义电子表格工作流程。这是使用Go在线将HTML转换为DIF和其他文档格式的专业解决方案。" urlsection="conversion/html-to-dif/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Go 将 HTML 转换为 DIF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 HTML 转换为 DIF 可能是一项复杂的任务。我们的 Go SDK 处理所有 HTML 到 DIF 格式的转换，同时保留源 HTML 电子表格的主要结构和逻辑内容。我们的Go库提供了在线将HTML转换为DIF文件的专业解决方案。该Cloud SDK为Go开发者提供了强大的功能，并确保高质量的DIF输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 Cells Cloud SDK 将 HTML 转换为 DIF 的 Go 代码示例" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.html")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "dif"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.dif")
	    if err2 != nil {
		    return
	    }
	    if _, err3 := file1.Write(value); err3 != nil {
		    return
	    }
	    file1.Close()
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells Cloud Go 库将 HTML 转换为 DIF。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Go 库并将引用（导入库）添加到您的项目中。</li>
<li>在go中打开源文件。</li>
<li>使用 `PutConvertWorkbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>go 版本 go1.13.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
