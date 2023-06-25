---
title: Save XLTM as JPG API for Java 
description: Using Aspose.Cells Cloud SDK for Java to save XLTM format file as JPG format file. 
url: /java/saveas/xltm-to-jpg/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API to save XLTM as JPG" h2="Java library to save XLTM as JPG" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in Java. This is a professional solution to save XLTM as JPG and other document formats online using Java." urlsection="saveas/xltm-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a XLTM file as JPG in Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLTM as JPG is a complex task. All XLTM to JPG format transitions is performed by our Java SDK while maintaining the source XLTM spreadsheet's main structural and logical content. Our Java library is a professional solution to save XLTM as JPG files online. This Cloud SDK gives Java developers powerful functionality and perfect JPG output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Java using REST API to save XLTM as JPG format" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xltm";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.jpg";
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
  
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Java API to save  XLTM as JPG" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cellsSaveAsPostDocumentSaveAs method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Maven 2.2.0 or newer</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
