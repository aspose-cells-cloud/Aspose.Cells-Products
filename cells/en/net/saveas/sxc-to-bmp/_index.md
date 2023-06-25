---
title: Save SXC as BMP API for C# 
description: Using Aspose.Cells Cloud SDK for C# to save SXC format file as BMP format file. 
url: /net/saveas/sxc-to-bmp/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API to save SXC as BMP" h2="C# library to save SXC as BMP" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in Net. This is a professional solution to save SXC as BMP and other document formats online using C#." urlsection="saveas/sxc-to-bmp/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a SXC file as BMP in C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from SXC as BMP is a complex task. All SXC to BMP format transitions is performed by our C# SDK while maintaining the source SXC spreadsheet's main structural and logical content. Our C# library is a professional solution to save SXC as BMP files online. This Cloud SDK gives C# developers powerful functionality and perfect BMP output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in C# using REST API to save SXC as BMP format" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.sxc";
    string newfilename = "Book1SaveAs.bmp";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use C# API to save  SXC as BMP" >}}
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
