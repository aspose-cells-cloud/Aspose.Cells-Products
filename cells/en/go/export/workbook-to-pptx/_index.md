---
title: Export WORKBOOK to PPTX from Excel using Cells Cloud SDK for Go  
description: Aspose.Cells Cloud REST API support exporting {0} to {1} format files using {2}. 
kwords: Excel, workbook, pptx, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Go to export objects from Excel WORKBOOK to PPTX","description": "How to use Cells Cloud SDK for Go to export objects from Excel WORKBOOK to PPTX","image": {"@type": "ImageObject"},"url": "/go/export/workbook-to-pptx/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel WORKBOOK to PPTX step 1", "image": {"@type": "ImageObject",},"url": "/go/export/workbook-to-pptx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel WORKBOOK to PPTX step 1", "image": {"@type": "ImageObject",},"url": "/go/export/workbook-to-pptx/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel WORKBOOK to PPTX step 1", "image": {"@type": "ImageObject",},"url": "/go/export/workbook-to-pptx/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Export WORKBOOK to PPTX from Excel" h2="Go library for exporting WORKBOOK to PPTX file" p="Use Export API of Cells Cloud to export Excel file internal object workflows in Go. This is a professional solution to export WORKBOOK to PPTX format file from spreadsheet online using Go." urlsection="export/workbook-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Export WORKBOOK object to PPTX format file using Cells Cloud SDK for Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST %}}
<br/>
Export WORKBOOK object to PPTX file from Excel file is a complex task. Export WORKBOOK to PPTX format transitions is performed by our Go SDK while maintaining the source WORKBOOK spreadsheet's main structural and logical content. Our Go library is a professional solution to export WORKBOOK objects to PPTX format files online. This Cloud SDK gives Go developers powerful functionality and perfect PPTX output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Code example in Go using REST API to export WORKBOOK to PPTX format from spreadsheet" gistPath="" %}}
  
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
	    postExportOpts.ObjectType = "workbook"
	    postExportOpts.Format = "pptx"
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
   
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Go to export objects from Excel WORKBOOK to PPTX" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Use the `postExport` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>go version go1.13.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
