---
title: Save FODS as XLS using Go 
description: Utilizing Aspose.Cells Cloud SDK for Go to save FODS format file as XLS format file. 
kwords: Excel, Save FODS as XLS, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save FODS as XLS using the Cells Cloud Go library.","description": "How to save FODS as XLS using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/fods-to-xls/","step": [{ "@type": "HowToStep","name": "How to save FODS as XLS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/fods-to-xls/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save FODS as XLS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/fods-to-xls/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save FODS as XLS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/fods-to-xls/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save FODS as XLS using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/fods-to-xls/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Save FODS as XLS" h2="Go library for saving FODS as XLS" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Go. This is a professional solution to save FODS as XLS and other document formats online using Go." urlsection="saveas/fods-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a FODS file as XLS in Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from FODS as XLS is a complex task. All FODS to XLS format transitions is performed by our Go SDK while maintaining the source FODS spreadsheet's main structural and logical content. Our Go library is a professional solution to save FODS as XLS files online. This Cloud SDK gives Go developers powerful functionality and perfect XLS output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go Code Example for saving FODS as XLS using REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.fods"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.xls"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to save FODS as XLS using the Cells Cloud Go library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Go library and add the reference (import the library) to your project.</li>
<li>Open the source file in go.</li>
<li>Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>go version go1.13.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
