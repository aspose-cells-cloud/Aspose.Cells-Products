---
title: Save TXT as ODS using Android 
description: Utilizing Aspose.Cells Cloud SDK for Android to save TXT format file as ODS format file. 
kwords: Excel, Save TXT as ODS, REST, Android
howto: How to save TXT as ODS using Aspose.Cells Cloud Android library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save TXT as ODS" h2="Android library for saving TXT as ODS" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Android. This is a professional solution to save TXT as ODS and other document formats online using Android." urlsection="saveas/txt-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a TXT file as ODS in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from TXT as ODS is a complex task. All TXT to ODS format transitions is performed by our Android SDK while maintaining the source TXT spreadsheet's main structural and logical content. Our Android library is a professional solution to save TXT as ODS files online. This Cloud SDK gives Android developers powerful functionality and perfect ODS output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android Code Example for saving TXT as ODS using REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.txt";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.ods";
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
