---
title: 将数字另存为 MD API for Go
description: 使用Aspose.Cells Cloud SDK for Go将NUMBERS格式文件保存为MD格式文件。
url: /zh/go/saveas/numbers-to-md/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="转到 API 将 NUMBERS 保存为 MD" h2="转到库将 NUMBERS 保存为 MD" p="使用 Cells SaveAs REST API 在 Go 中创建自定义电子表格工作流程。这是使用 Go 在线将 NUMBERS 保存为 MD 和其他文档格式的专业解决方案。" urlsection="saveas/numbers-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Go 中将 NUMBERS 文件保存为 MD" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 NUMBERS 中的文件格式保存为 MD 是一项复杂的任务。所有 NUMBERS 到 MD 格式的转换均由我们的 Go SDK 执行，同时保留源 NUMBERS 电子表格的主要结构和逻辑内容。我们的 Go 库是在线将 NUMBERS 保存为 MD 文件的专业解决方案。该Cloud SDK为Go开发者提供了强大的功能和完美的MD输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Go 中使用 REST API 将 NUMBERS 保存为 MD 格式的代码示例" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.numbers"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.md"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Go API将NUMBERS保存为MD" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 CellsSaveAsPostDocumentSaveAs 方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>go 版本 go1.13.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
