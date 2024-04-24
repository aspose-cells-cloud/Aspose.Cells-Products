---
title: Save XLTM as DOCX using NodeJS 
description: Utilizing Aspose.Cells Cloud SDK for NodeJS to save XLTM format file as DOCX format file. 
kwords: Excel, Save XLTM as DOCX, REST, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLTM as DOCX using the Cells Cloud NodeJS library.","description": "How to save XLTM as DOCX using the Cells Cloud NodeJS library.","image": {"@type": "ImageObject"},"url": "/nodejs/saveas/xltm-to-docx/","step": [{ "@type": "HowToStep","name": "How to save XLTM as DOCX using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xltm-to-docx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLTM as DOCX using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xltm-to-docx/","text": "Install NodeJS library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLTM as DOCX using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xltm-to-docx/","text": "Open the source file in JavaScript.",},{ "@type": "HowToStep","name": "How to save XLTM as DOCX using the Cells Cloud NodeJS library. step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/saveas/xltm-to-docx/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Save XLTM as DOCX" h2="NodeJS library for saving XLTM as DOCX" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in NodeJS. This is a professional solution to save XLTM as DOCX and other document formats online using NodeJS." urlsection="saveas/xltm-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a XLTM file as DOCX in NodeJS" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLTM as DOCX is a complex task. All XLTM to DOCX format transitions is performed by our NodeJS SDK while maintaining the source XLTM spreadsheet's main structural and logical content. Our NodeJS library is a professional solution to save XLTM as DOCX files online. This Cloud SDK gives NodeJS developers powerful functionality and perfect DOCX output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="NodeJS Code Example for saving XLTM as DOCX using REST API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xltm",
      folder: "CellsTests",
      newfilename: "Book1Saveas.docx",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to save XLTM as DOCX using the Cells Cloud NodeJS library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install NodeJS library and add the reference (import the library) to your project.</li>
<li>Open the source file in JavaScript.</li>
<li>Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>node v6.17.1 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
