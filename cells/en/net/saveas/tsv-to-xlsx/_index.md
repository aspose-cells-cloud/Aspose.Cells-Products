---
title: Save TSV as XLSX API for C# 
description: Using Aspose.Cells Cloud SDK for C# to save TSV format file as XLSX format file. 
url: /net/saveas/tsv-to-xlsx/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API to save TSV as XLSX" h2="C# library to save TSV as XLSX" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in Net. This is a professional solution to save TSV as XLSX and other document formats online using C#." urlsection="saveas/tsv-to-xlsx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a TSV file as XLSX in C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from TSV as XLSX is a complex task. All TSV to XLSX format transitions is performed by our C# SDK while maintaining the source TSV spreadsheet's main structural and logical content. Our C# library is a professional solution to save TSV as XLSX files online. This Cloud SDK gives C# developers powerful functionality and perfect XLSX output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in C# using REST API to save TSV as XLSX format" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.tsv";
    string newfilename = "Book1SaveAs.xlsx";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use C# API to save  TSV as XLSX" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call CellsSaveAsPostDocumentSaveAs method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>NET Framework 4.5.2 or newer</li>
<li>Net Standard 2.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
