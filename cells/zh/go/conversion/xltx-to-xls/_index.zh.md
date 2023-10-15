---
title: 使用 Go 将 XLTX 转换为 XLS
description: 利用Aspose.Cells Cloud SDK for Go将XLTX格式文件转换为XLS格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 XLTX 转换为 XLS" h2="用于将 XLTX 转换为 XLS 的 Go 库" p="使用 Cells 云的转换 API 在 Go 项目中创建自定义电子表格工作流程。这是使用Go在线将XLTX转换为XLS和其他文档格式的专业解决方案。" urlsection="conversion/xltx-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="使用 Cells Cloud SDK for Go 将 XLTX 转换为 XLS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLTX 转换为 XLS 可能是一项复杂的任务。我们的 Go SDK 处理所有 XLTX 到 XLS 格式的转换，同时保留源 XLTX 电子表格的主要结构和逻辑内容。我们的 Go 库提供了在线将 XLTX 转换为 XLS 文件的专业解决方案。该Cloud SDK为Go开发人员提供了强大的功能，并确保高质量的XLS输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="使用 Cells Cloud SDK 将 XLTX 转换为 XLS 的 Go 代码示例" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.xltx")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "xls"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.xls")
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Go将Excel文件转换为其他格式XLTX转XLS" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `PutConvertWorkbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>go 版本 go1.13.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
