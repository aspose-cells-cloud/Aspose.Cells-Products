---
title: Save FODS as GIF using Go 
description: Utilizing Aspose.Cells Cloud SDK for Go to save FODS format file as GIF format file. 
kwords: Excel, Save FODS as GIF, REST, Go
howto: How to save FODS as GIF using Aspose.Cells Cloud Go library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save FODS as GIF" h2="Go library for saving FODS as GIF" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Go. This is a professional solution to save FODS as GIF and other document formats online using Go." urlsection="saveas/fods-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a FODS file as GIF in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from FODS as GIF is a complex task. All FODS to GIF format transitions is performed by our Go SDK while maintaining the source FODS spreadsheet's main structural and logical content. Our Go library is a professional solution to save FODS as GIF files online. This Cloud SDK gives Go developers powerful functionality and perfect GIF output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go Code Example for saving FODS as GIF using REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.fods"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.gif"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save FODS as GIF using the Cells Cloud Go library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Go library and add the reference (import the library) to your project.</li>
<li>Open the source file in go.</li>
<li>Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>go version go1.13.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
