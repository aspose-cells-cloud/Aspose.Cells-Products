---
title: 使用 Go 将 ODS 保存为 DOCX
description: 利用Aspose.Cells Cloud SDK for Go将ODS格式文件保存为DOCX格式文件。
kwords: Excel, Save ODS as DOCX, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save ODS as DOCX using the Cells Cloud Go library.","description": "How to save ODS as DOCX using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/ods-to-docx/","step": [{ "@type": "HowToStep","name": "How to save ODS as DOCX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/ods-to-docx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save ODS as DOCX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/ods-to-docx/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save ODS as DOCX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/ods-to-docx/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save ODS as DOCX using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/ods-to-docx/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 ODS 保存为 DOCX" h2="用于将 ODS 保存为 DOCX 的 Go 库" p="使用 Cells Cloud 的 SaveAs API 在 Go 中创建自定义电子表格工作流程。这是使用 Go 在线将 ODS 保存为 DOCX 等文档格式的专业解决方案。" urlsection="saveas/ods-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="在 Go 中将 ODS 文件保存为 DOCX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 ODS 中的文件格式保存为 DOCX 是一项复杂的任务。所有 ODS 到 DOCX 格式的转换均由我们的 Go SDK 执行，同时保留源 ODS 电子表格的主要结构和逻辑内容。我们的 Go 库是在线将 ODS 保存为 DOCX 文件的专业解决方案。这个Cloud SDK为Go开发者提供了强大的功能和完美的DOCX输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 REST 将 ODS 保存为 DOCX 的 Go 代码示例 API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.ods"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.docx"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells Cloud Go 库将 ODS 保存为 DOCX。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Go 库并将引用（导入库）添加到您的项目中。</li>
<li>在go中打开源文件。</li>
<li>使用 `PostWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>go 版本 go1.13.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
