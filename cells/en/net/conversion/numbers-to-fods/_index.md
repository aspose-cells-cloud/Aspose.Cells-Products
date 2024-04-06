---
title: Convert NUMBERS to FODS using C# 
description: Utilizing the Aspose.Cells Cloud SDK for C# to convert a NUMBERS format file to a FODS format file. 
kwords: Excel, Convert NUMBERS to FODS, REST, C#
howto: How to convert NUMBERS to FODS using Aspose.Cells Cloud C# library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert NUMBERS to FODS" h2="C# library for converting NUMBERS to FODS" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Net projects. This is a professional solution to convert NUMBERS to FODS and other document formats online using C#." urlsection="conversion/numbers-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert NUMBERS to FODS using Cells Cloud SDK for C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from NUMBERS to FODS can be a complex task. Our C# SDK handles all NUMBERS to FODS format conversions while preserving the main structural and logical content of the source NUMBERS spreadsheet. Our C# library provides a professional solution for converting NUMBERS to FODS files online. This Cloud SDK empowers C# developers with powerful functionality and ensures high-quality FODS output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Code Example for converting NUMBERS to FODS using Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string format = "fods";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.fods";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to convert NUMBERS to FODS using the Cells Cloud Net library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install C# library and add the reference (import the library) to your project.</li>
<li>Open the source file in C#</li>
<li>Use the `PutConvertWorkbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>NET Framework 4.5.2 or newer</li>
<li>Net Standard 2.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
