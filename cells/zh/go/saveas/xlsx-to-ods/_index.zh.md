﻿---
title: 将 XLSX 保存为 ODS API for Go
description: 用于 Microsoft Excel 和 OpenOffice Calc 的云 API 和 SDK。将电子表格转换为其他格式文件。
url: /zh/go/saveas/xlsx-to-ods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="转到 API 将 XLSX 另存为 ODS" h2="去图书馆将XLSX保存为ODS" p="使用 Cells SaveAs REST API 在 Go 中创建自定义电子表格工作流程。这是一个使用 Go 在线将 XLSX 保存为 ODS 和其他文档格式的专业解决方案。" urlsection="saveas/xlsx-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Go 中将 XLSX 文件另存为 ODS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLSX 中的文件格式保存为 ODS 是一项复杂的任务。所有 XLSX 到 ODS 格式的转换都由我们的 Go SDK 执行，同时保持源 XLSX 电子表格的主要结构和逻辑内容。我们的 Go 库是将 XLSX 在线保存为 ODS 文件的专业解决方案。此 Cloud SDK 为 Go 开发者提供了强大的功能和完美的 ODS 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Go 中的代码示例使用 REST API 将 XLSX 保存为 ODS 格式" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.xlsx"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.ods"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Go API 将 XLSX 保存为 ODS" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获得免费的 API 配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 CellsSaveAsPostDocumentSaveAs 方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>go 版本 go1.13.0 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}