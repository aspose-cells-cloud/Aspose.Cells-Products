---
title: Save PNG as XLTM using Android 
description: Utilizing Aspose.Cells Cloud SDK for Android to save PNG format file as XLTM format file. 
kwords: Excel, Save PNG as XLTM, REST, Android
howto: How to save PNG as XLTM using Aspose.Cells Cloud Android library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save PNG as XLTM" h2="Android library for saving PNG as XLTM" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Android. This is a professional solution to save PNG as XLTM and other document formats online using Android." urlsection="saveas/png-to-xltm/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a PNG file as XLTM in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from PNG as XLTM is a complex task. All PNG to XLTM format transitions is performed by our Android SDK while maintaining the source PNG spreadsheet's main structural and logical content. Our Android library is a professional solution to save PNG as XLTM files online. This Cloud SDK gives Android developers powerful functionality and perfect XLTM output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android Code Example for saving PNG as XLTM using REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.png";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xltm";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Android to save Excel files as other formats" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Use the `postWorkbookSaveAs` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Android 7 or newer</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
