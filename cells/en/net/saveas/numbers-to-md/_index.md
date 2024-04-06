---
title: Save NUMBERS as MD using C# 
description: Utilizing Aspose.Cells Cloud SDK for C# to save NUMBERS format file as MD format file. 
kwords: Excel, Save NUMBERS as MD, REST, C#
howto: How to save NUMBERS as MD using Aspose.Cells Cloud C# library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save NUMBERS as MD" h2="C# library for saving NUMBERS as MD" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Net. This is a professional solution to save NUMBERS as MD and other document formats online using C#." urlsection="saveas/numbers-to-md/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a NUMBERS file as MD in C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from NUMBERS as MD is a complex task. All NUMBERS to MD format transitions is performed by our C# SDK while maintaining the source NUMBERS spreadsheet's main structural and logical content. Our C# library is a professional solution to save NUMBERS as MD files online. This Cloud SDK gives C# developers powerful functionality and perfect MD output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Code Example for saving NUMBERS as MD using REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string newfilename = "Book1SaveAs.md";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save NUMBERS as MD using the Cells Cloud Net library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install C# library and add the reference (import the library) to your project.</li>
<li>Open the source file in C#</li>
<li>Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>NET Framework 4.5.2 or newer</li>
<li>Net Standard 2.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
