---
title: Save TXT as XLSX using C# 
description: Utilizing Aspose.Cells Cloud SDK for C# to save TXT format file as XLSX format file. 
kwords: Excel, Save TXT as XLSX, REST, C#
howto: How to save TXT as XLSX using Aspose.Cells Cloud C# library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save TXT as XLSX" h2="C# library for saving TXT as XLSX" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Net. This is a professional solution to save TXT as XLSX and other document formats online using C#." urlsection="saveas/txt-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a TXT file as XLSX in C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from TXT as XLSX is a complex task. All TXT to XLSX format transitions is performed by our C# SDK while maintaining the source TXT spreadsheet's main structural and logical content. Our C# library is a professional solution to save TXT as XLSX files online. This Cloud SDK gives C# developers powerful functionality and perfect XLSX output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Code Example for saving TXT as XLSX using REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.txt";
    string newfilename = "Book1SaveAs.xlsx";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save TXT as XLSX using the Cells Cloud Net library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install C# library and add the reference (import the library) to your project.</li>
<li>Open the source file in C#</li>
<li>Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>NET Framework 4.5.2 or newer</li>
<li>Net Standard 2.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
