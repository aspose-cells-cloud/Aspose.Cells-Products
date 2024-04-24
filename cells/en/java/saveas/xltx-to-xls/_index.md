---
title: Save XLTX as XLS using Java 
description: Utilizing Aspose.Cells Cloud SDK for Java to save XLTX format file as XLS format file. 
kwords: Excel, Save XLTX as XLS, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLTX as XLS using the Cells Cloud Java library.","description": "How to save XLTX as XLS using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/saveas/xltx-to-xls/","step": [{ "@type": "HowToStep","name": "How to save XLTX as XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/xltx-to-xls/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLTX as XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/xltx-to-xls/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLTX as XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/xltx-to-xls/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to save XLTX as XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/xltx-to-xls/","text": "Use the `postWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Save XLTX as XLS" h2="Java library for saving XLTX as XLS" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Java. This is a professional solution to save XLTX as XLS and other document formats online using Java." urlsection="saveas/xltx-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a XLTX file as XLS in Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLTX as XLS is a complex task. All XLTX to XLS format transitions is performed by our Java SDK while maintaining the source XLTX spreadsheet's main structural and logical content. Our Java library is a professional solution to save XLTX as XLS files online. This Cloud SDK gives Java developers powerful functionality and perfect XLS output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Code Example for saving XLTX as XLS using REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xltx";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xls";
    String folder ="CellsTests";
    try 
    {
        CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
        cellsApi.cellsSaveAsPostDocumentSaveAs(name , saveOptions,newfilename,false,false,folder,null,null,null,true);                       
    }
    catch(Exception exception )
    {
        System.out.print(exception);
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to save XLTX as XLS using the Cells Cloud Java library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Java library and add the reference (import the library) to your project.</li>
<li>Open the source file in Java.</li>
<li>Use the `postWorkbookSaveAs` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Maven 2.2.0 or newer</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
