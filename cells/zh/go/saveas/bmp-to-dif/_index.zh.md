---
title: 使用 Go 将 BMP 保存为 DIF
description: 利用Aspose.Cells Cloud SDK for Go将BMP格式文件保存为DIF格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 BMP 保存为 DIF" h2="将 BMP 保存为 DIF 的 Go 库" p="使用 Cells Cloud 的 SaveAs API 在 Go 中创建自定义电子表格工作流程。这是使用Go在线将BMP保存为DIF等文档格式的专业解决方案。" urlsection="saveas/bmp-to-dif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Go 中将 BMP 文件保存为 DIF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 BMP 中的文件格式保存为 DIF 是一项复杂的任务。所有 BMP 到 DIF 格式的转换均由我们的 Go SDK 执行，同时保留源 BMP 电子表格的主要结构和逻辑内容。我们的Go库是在线将BMP保存为DIF文件的专业解决方案。这个Cloud SDK为Go开发者提供了强大的功能和完美的DIF输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="使用 REST API 将 BMP 保存为 DIF 的 Go 代码示例" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.bmp"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.dif"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Go将Excel文件保存为其他格式BMP保存为DIF" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `PostWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>go 版本 go1.13.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
