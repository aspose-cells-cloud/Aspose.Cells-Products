---
title: Convert XML to SXC via Go 
description: Create, Edit or Convert Excel files with REST API & Open Source Go SDK
url: /go/conversion/xml-to-sxc/
family: cells
platformtag: go
feature: conversion
informat: XML
outformat: SXC
platform: Go
otherformats: SVG HTML MD CSV TXT XLSB XLT DIF XLTM XLSX TIFF XLSM XPS ODS SXC XLTX 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XML to SXC with Go" h2="Read, Edit & Export Excel data to other formats like SXC with Open Source Cloud SDK for Go">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XML to SXC Conversion in the Cloud" %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApiService``` with API Key, App SID & Server
1. Upload XML file to default Cloud Storage with ```CellsAPI.UploadFile``` method
1. Call ```CellsSaveAsPostDocumentSaveAs``` method to get the resultant SXC file
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel API & Go SDK" %}}
Get Excel Cloud SDK for Go source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-go) to compile the SDK yourself or head to the [Releases](https://releases.aspose.cloud/) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Go Code for XML to SXC Conversion" gistPath="" %}}
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go
apiKey := "XXXXX" //sepcify App Key
appSid := "XXXXX" //sepcify App SID
apiServer := "https://api.aspose.cloud/v3.0"
dataFolder := "../../data/"
remoteFolder := "GoFiles"
name := "template.xml"
newFileName := "output.sxc"

//Instantiate Aspose Cells API SDK
CellsAPI := NewCellsApiService(apiKey, appSid, apiServer)
args := new(UploadFileOpts)
args.Path = remoteFolder + "/" + name
file := os.Open(dataFolder + "/" + name)
_, _, err = CellsAPI.UploadFile(file, args)
if err == nil {
	args1 := new(CellsSaveAsPostDocumentSaveAsOpts)
	args1.Name = name
	args1.Newfilename = remoteFolder + "/" + newFileName
	args1.Folder = remoteFolder

	response, httpResponse, err := CellsAPI.CellsSaveAsPostDocumentSaveAs(args1)
}
if err != nil {
	fmt.Println(err)
}
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}