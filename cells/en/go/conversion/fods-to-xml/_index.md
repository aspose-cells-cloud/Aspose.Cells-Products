---
title: Convert FODS to XML using Go 
description: Utilizing the Aspose.Cells Cloud SDK for Go to convert a FODS format file to a XML format file. 
kwords: Excel, Convert FODS to XML, REST, Go
howto: How to convert FODS to XML using Aspose.Cells Cloud Go library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert FODS to XML" h2="Go library for converting FODS to XML" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Go projects. This is a professional solution to convert FODS to XML and other document formats online using Go." urlsection="conversion/fods-to-xml/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert FODS to XML using Cells Cloud SDK for Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from FODS to XML can be a complex task. Our Go SDK handles all FODS to XML format conversions while preserving the main structural and logical content of the source FODS spreadsheet. Our Go library provides a professional solution for converting FODS to XML files online. This Cloud SDK empowers Go developers with powerful functionality and ensures high-quality XML output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go Code Example for converting FODS to XML using Cells Cloud SDK" gistPath="" %}}
 
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
	    convertWorkbookOpts.Format = "xml"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.xml")
	    if err2 != nil {
		    return
	    }
	    if _, err3 := file1.Write(value); err3 != nil {
		    return
	    }
	    file1.Close()
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to convert FODS to XML using the Cells Cloud Go library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Go library and add the reference (import the library) to your project.</li>
<li>Open the source file in go.</li>
<li>Use the `PutConvertWorkbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>go version go1.13.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
