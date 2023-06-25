---
title: Save BMP as XLSX API for Android 
description: Using Aspose.Cells Cloud SDK for Android to save BMP format file as XLSX format file. 
url: /android/saveas/bmp-to-xlsx/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API to save BMP as XLSX" h2="Android library to save BMP as XLSX" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in Android. This is a professional solution to save BMP as XLSX and other document formats online using Android." urlsection="saveas/bmp-to-xlsx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a BMP file as XLSX in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from BMP as XLSX is a complex task. All BMP to XLSX format transitions is performed by our Android SDK while maintaining the source BMP spreadsheet's main structural and logical content. Our Android library is a professional solution to save BMP as XLSX files online. This Cloud SDK gives Android developers powerful functionality and perfect XLSX output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Android using REST API to save BMP as XLSX format" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.bmp";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xlsx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Java API to save  BMP as XLSX" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cellsSaveAsPostDocumentSaveAs method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Android 7 or newer</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
