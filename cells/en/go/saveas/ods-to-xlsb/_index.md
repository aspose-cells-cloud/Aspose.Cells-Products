---
title: Save ODS as XLSB API for Go 
description: Using Aspose.Cells Cloud SDK for Go to save ODS format file as XLSB format file. 
url: /go/saveas/ods-to-xlsb/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Go API to save ODS as XLSB" h2="Go library to save ODS as XLSB" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in Go. This is a professional solution to save ODS as XLSB and other document formats online using Go." urlsection="saveas/ods-to-xlsb/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a ODS file as XLSB in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from ODS as XLSB is a complex task. All ODS to XLSB format transitions is performed by our Go SDK while maintaining the source ODS spreadsheet's main structural and logical content. Our Go library is a professional solution to save ODS as XLSB files online. This Cloud SDK gives Go developers powerful functionality and perfect XLSB output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Go using REST API to save ODS as XLSB format" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.ods"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.xlsb"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Go API to save  ODS as XLSB" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call CellsSaveAsPostDocumentSaveAs method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>go version go1.13.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
