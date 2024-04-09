---
title: 使用 Go 将 HTML 保存为 XLSB
description: 利用Aspose.Cells Cloud SDK for Go将HTML格式文件保存为XLSB格式文件。
kwords: Excel, Save HTML as XLSB, REST, Go
howto: How to save HTML as XLSB using Aspose.Cells Cloud Go library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 HTML 另存为 XLSB" h2="用于将 HTML 保存为 XLSB 的 Go 库" p="使用 Cells Cloud 的 SaveAs API 在 Go 中创建自定义电子表格工作流程。这是使用Go在线将HTML保存为XLSB等文档格式的专业解决方案。" urlsection="saveas/html-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="在 Go 中将 HTML 文件另存为 XLSB" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 HTML 中的文件格式保存为 XLSB 是一项复杂的任务。所有 HTML 到 XLSB 格式的转换均由我们的 Go SDK 执行，同时保留源 HTML 电子表格的主要结构和逻辑内容。我们的Go库是在线将HTML保存为XLSB文件的专业解决方案。该 Cloud SDK 为 Go 开发人员提供了强大的功能和完美的 XLSB 输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 REST API 将 HTML 保存为 XLSB 的 Go 代码示例" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.html"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.xlsb"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Go 库将 HTML 另存为 XLSB。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Go 库并将引用（导入库）添加到您的项目中。</li>
<li>在go中打开源文件。</li>
<li>使用 `PostWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>go 版本 go1.13.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
