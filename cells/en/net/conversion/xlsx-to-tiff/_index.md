---
title: Convert XLSX to TIFF using C# 
description: Utilizing the Aspose.Cells Cloud SDK for C# to convert a XLSX format file to a TIFF format file. 
kwords: Excel, Convert XLSX to TIFF, REST, C#
howto: How to convert XLSX to TIFF using Aspose.Cells Cloud C# library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert XLSX to TIFF" h2="C# library for converting XLSX to TIFF" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Net projects. This is a professional solution to convert XLSX to TIFF and other document formats online using C#." urlsection="conversion/xlsx-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert XLSX to TIFF using Cells Cloud SDK for C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XLSX to TIFF can be a complex task. Our C# SDK handles all XLSX to TIFF format conversions while preserving the main structural and logical content of the source XLSX spreadsheet. Our C# library provides a professional solution for converting XLSX to TIFF files online. This Cloud SDK empowers C# developers with powerful functionality and ensures high-quality TIFF output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Code Example for converting XLSX to TIFF using Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsx";
    string format = "tiff";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.tiff";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to convert XLSX to TIFF using the Cells Cloud Net library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install C# library and add the reference (import the library) to your project.</li>
<li>Open the source file in C#</li>
<li>Use the `PutConvertWorkbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>NET Framework 4.5.2 or newer</li>
<li>Net Standard 2.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
