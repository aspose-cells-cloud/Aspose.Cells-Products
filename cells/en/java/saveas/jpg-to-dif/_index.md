---
title: Save JPG as DIF API for Java 
description: Using Aspose.Cells Cloud SDK for Java to save JPG format file as DIF format file. 
url: /java/saveas/jpg-to-dif/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API to save JPG as DIF" h2="Java library to save JPG as DIF" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in Java. This is a professional solution to save JPG as DIF and other document formats online using Java." urlsection="saveas/jpg-to-dif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a JPG file as DIF in Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from JPG as DIF is a complex task. All JPG to DIF format transitions is performed by our Java SDK while maintaining the source JPG spreadsheet's main structural and logical content. Our Java library is a professional solution to save JPG as DIF files online. This Cloud SDK gives Java developers powerful functionality and perfect DIF output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Java using REST API to save JPG as DIF format" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.jpg";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.dif";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Java API to save  JPG as DIF" >}}
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
