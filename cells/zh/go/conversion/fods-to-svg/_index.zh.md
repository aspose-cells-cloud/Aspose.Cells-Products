---
title: 使用 Go 将 FODS 转换为 SVG
description: 利用Aspose.Cells Cloud SDK for Go将FODS格式文件转换为SVG格式文件。
kwords: Excel, Convert FODS to SVG, REST, Go
howto: How to convert FODS to SVG using Aspose.Cells Cloud Go library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 FODS 转换为 SVG" h2="用于将 FODS 转换为 SVG 的 Go 库" p="使用 Cells 云的转换 API 在 Go 项目中创建自定义电子表格工作流程。这是使用 Go 在线将 FODS 转换为 SVG 等文档格式的专业解决方案。" urlsection="conversion/fods-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Go 将 FODS 转换为 SVG" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 FODS 转换为 SVG 可能是一项复杂的任务。我们的 Go SDK 处理所有 FODS 到 SVG 格式的转换，同时保留源 FODS 电子表格的主要结构和逻辑内容。我们的 Go 库提供了在线将 FODS 转换为 SVG 文件的专业解决方案。该Cloud SDK为Go开发者提供了强大的功能，并保证了高质量的SVG输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 Cells Cloud SDK 将 FODS 转换为 SVG 的 Go 代码示例" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.fods")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "svg"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.svg")
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Go 库将 FODS 转换为 SVG。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Go 库并将引用（导入库）添加到您的项目中。</li>
<li>在go中打开源文件。</li>
<li>使用 `PutConvertWorkbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>go 版本 go1.13.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
