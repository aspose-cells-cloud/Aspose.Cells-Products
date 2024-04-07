---
title: Save FODS as XLT using Java 
description: Utilizing Aspose.Cells Cloud SDK for Java to save FODS format file as XLT format file. 
kwords: Excel, Save FODS as XLT, REST, Java
howto: How to save FODS as XLT using Aspose.Cells Cloud Java library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save FODS as XLT" h2="Java library for saving FODS as XLT" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Java. This is a professional solution to save FODS as XLT and other document formats online using Java." urlsection="saveas/fods-to-xlt/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a FODS file as XLT in Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from FODS as XLT is a complex task. All FODS to XLT format transitions is performed by our Java SDK while maintaining the source FODS spreadsheet's main structural and logical content. Our Java library is a professional solution to save FODS as XLT files online. This Cloud SDK gives Java developers powerful functionality and perfect XLT output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Code Example for saving FODS as XLT using REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.fods";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xlt";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save FODS as XLT using the Cells Cloud Java library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Java library and add the reference (import the library) to your project.</li>
<li>Open the source file in Java.</li>
<li>Use the `postWorkbookSaveAs` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Maven 2.2.0 or newer</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
