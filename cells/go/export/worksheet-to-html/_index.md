---
title: Export Worksheet to HTML file via Go
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Export workbok or interanl object to kinds of format file in the Cloud.
url: /go/export/worksheet-to-html/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Export Worksheet to HTML file in the Cloud" h2="Excel & OpenOffice spreadsheet export with open source Cloud SDK for Go">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export Worksheet to HTML file in Cloud SDK for Go " %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```LightCellsAPI``` with Client Id, Client Secret, Base URL & API version
1. Call ```PostExport``` method to get the resultant HTML stream
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for .NET source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-go) to compile the SDK yourself or head to the [Releases](https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/releases) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/#/LightCells/PostExport) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Go Code for WORKSHEET to HTML Conversion" gistPath="" %}}
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
	postExportOpts.ObjectType = "worksheet"
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

{{% /blocks/products/pf/agp/code-autogen %}}
{{% blocks/products/cells/cells-cloud-api-run-export  InputFormat=".xlsx,.xls,.csv,.txt,.ods"  OutputFormat=html  ExportObjectType=worksheet %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
