---
title:  XLTM 到 JSON 转换 API for Go
description: 使用Aspose.Cells Cloud SDK for Go将XLTM格式文件转换为JSON格式文件。
url: /zh/go/conversion/xltm-to-json/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="去API将XLTM转换为JSON" h2="Go 库将 XLTM 转换为 JSON" p="使用 Cells Conversion REST API 在 Go 中创建自定义电子表格工作流程。这是使用 Go 在线将 XLTM 转换为 JSON 等文档格式的专业解决方案。" urlsection="conversion/xltm-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Go 中将 XLTM 文件转换为 JSON" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLTM 转换为 JSON 是一项复杂的任务。所有 XLTM 到 JSON 格式的转换均由我们的 Go SDK 执行，同时保留源 XLTM 电子表格的主要结构和逻辑内容。我们的 Go 库是在线将 XLTM 转换为 JSON 文件的专业解决方案。这个Cloud SDK为Go开发者提供了强大的功能和完美的JSON输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Go 中使用 REST API 将 XLTM 转换为 JSON 格式的代码示例" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.xltm")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "json"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.json")
	    if err2 != nil {
		    return
	    }
	    if _, err3 := file1.Write(value); err3 != nil {
		    return
	    }
	    file1.Close()
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Go API将XLTM转换为JSON" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 CellsWorkbookPutConvertWorkbook 方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>go 版本 go1.13.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
