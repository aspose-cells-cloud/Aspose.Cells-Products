---
title: Convert TXT to SXC using C# 
description: Utilizing the Aspose.Cells Cloud SDK for C# to convert a TXT format file to a SXC format file. 

---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convert TXT to SXC" h2="C# library for converting TXT to SXC" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Net projects. This is a professional solution to convert TXT to SXC and other document formats online using C#." urlsection="conversion/txt-to-sxc/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert TXT to SXC using Cells Cloud SDK for C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from TXT to SXC can be a complex task. Our C# SDK handles all TXT to SXC format conversions while preserving the main structural and logical content of the source TXT spreadsheet. Our C# library provides a professional solution for converting TXT to SXC files online. This Cloud SDK empowers C# developers with powerful functionality and ensures high-quality SXC output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# Code Example for converting TXT to SXC using Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.txt";
    string format = "sxc";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.sxc";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Net to convert Excel files to other formats TXT to SXC" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Use the `PutConvertWorkbook` method to retrieve the resulting stream.</li>
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
