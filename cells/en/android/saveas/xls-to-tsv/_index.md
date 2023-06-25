---
title: Save XLS as TSV API for Android 
description: Using Aspose.Cells Cloud SDK for Android to save XLS format file as TSV format file. 
url: /android/saveas/xls-to-tsv/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API to save XLS as TSV" h2="Android library to save XLS as TSV" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in Android. This is a professional solution to save XLS as TSV and other document formats online using Android." urlsection="saveas/xls-to-tsv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a XLS file as TSV in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLS as TSV is a complex task. All XLS to TSV format transitions is performed by our Android SDK while maintaining the source XLS spreadsheet's main structural and logical content. Our Android library is a professional solution to save XLS as TSV files online. This Cloud SDK gives Android developers powerful functionality and perfect TSV output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Android using REST API to save XLS as TSV format" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xls";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.tsv";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Java API to save  XLS as TSV" >}}
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
