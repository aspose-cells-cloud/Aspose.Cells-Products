---
title: Convert XLSM to WMF using Go 
description: Utilizing the Aspose.Cells Cloud SDK for Go to convert a XLSM format file to a WMF format file. 
kwords: Excel, Convert XLSM to WMF, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLSM to WMF using the Cells Cloud Go library.","description": "How to convert XLSM to WMF using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/conversion/xlsm-to-wmf/","step": [{ "@type": "HowToStep","name": "How to convert XLSM to WMF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/xlsm-to-wmf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLSM to WMF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/xlsm-to-wmf/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLSM to WMF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/xlsm-to-wmf/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to convert XLSM to WMF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/conversion/xlsm-to-wmf/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert XLSM to WMF" h2="Go library for converting XLSM to WMF" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Go projects. This is a professional solution to convert XLSM to WMF and other document formats online using Go." urlsection="conversion/xlsm-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert XLSM to WMF using Cells Cloud SDK for Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XLSM to WMF can be a complex task. Our Go SDK handles all XLSM to WMF format conversions while preserving the main structural and logical content of the source XLSM spreadsheet. Our Go library provides a professional solution for converting XLSM to WMF files online. This Cloud SDK empowers Go developers with powerful functionality and ensures high-quality WMF output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go Code Example for converting XLSM to WMF using Cells Cloud SDK" gistPath="" %}}
 
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    file, err := os.Open("Book1.xlsm")
	    if err != nil {
		    return
	    }
	    convertWorkbookOpts := new(asposecellscloud.CellsWorkbookPutConvertWorkbookOpts)
	    convertWorkbookOpts.Format = "wmf"
	    value, response, err1 := instance.CellsWorkbookPutConvertWorkbook(file, convertWorkbookOpts)
	    if err1 != nil {
		    return
	    }
	    file1, err2 := os.Create("Dest.wmf")
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to convert XLSM to WMF using the Cells Cloud Go library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Go library and add the reference (import the library) to your project.</li>
<li>Open the source file in go.</li>
<li>Use the `PutConvertWorkbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>go version go1.13.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
