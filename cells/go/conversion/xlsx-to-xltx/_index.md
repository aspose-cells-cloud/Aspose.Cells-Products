---
title: Convert XLSX to XLTX via Go 
description: Create, Edit or Convert Excel files with REST API & Open Source Go SDK
url: /go/conversion/xlsx-to-xltx/
family: cells
platformtag: go
feature: conversion
informat: XLSX
outformat: XLTX
platform: Go
otherformats: MHTML SXC XLS XPS TSV SVG TIFF XLTM XML CSV DIF TXT ODS XLSM XLSB PDF 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XLSX to XLTX with Go" h2="Read, Edit & Export Excel data to other formats like XLTX with Open Source Cloud SDK for Go">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSX to XLTX Conversion in the Cloud" %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApiService``` with API Key, App SID & Server
1. Upload XLSX file to default Cloud Storage with ```CellsAPI.UploadFile``` method
1. Call ```CellsSaveAsPostDocumentSaveAs``` method to get the resultant XLTX file
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel API & Go SDK" %}}
Get Excel Cloud SDK for Go source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-go) to compile the SDK yourself or head to the [Releases](https://releases.aspose.cloud/) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Go Code for XLSX to XLTX Conversion" gistPath="" %}}
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go
apiKey := "XXXXX" //sepcify App Key
appSid := "XXXXX" //sepcify App SID
apiServer := "https://api.aspose.cloud/v3.0"
dataFolder := "../../data/"
remoteFolder := "GoFiles"
name := "template.xlsx"
newFileName := "output.xltx"
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
	response, httpResponse, err := CellsAPI.CellsSaveAsPostDocumentSaveAs(args1) }
if err != nil {
	fmt.Println(err) }
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}