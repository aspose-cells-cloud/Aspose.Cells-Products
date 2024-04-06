---
title: Convert XLSM to XLS using C# 
description: Utilizing the Aspose.Cells Cloud SDK for C# to convert a XLSM format file to a XLS format file. 
kwords: Excel, Convert XLSM to XLS, REST, C#
howto: How to convert XLSM to XLS using Aspose.Cells Cloud C# library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert XLSM to XLS" h2="C# library for converting XLSM to XLS" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Net projects. This is a professional solution to convert XLSM to XLS and other document formats online using C#." urlsection="conversion/xlsm-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert XLSM to XLS using Cells Cloud SDK for C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XLSM to XLS can be a complex task. Our C# SDK handles all XLSM to XLS format conversions while preserving the main structural and logical content of the source XLSM spreadsheet. Our C# library provides a professional solution for converting XLSM to XLS files online. This Cloud SDK empowers C# developers with powerful functionality and ensures high-quality XLS output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Code Example for converting XLSM to XLS using Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsm";
    string format = "xls";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xls";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to convert XLSM to XLS using the Cells Cloud Net library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install C# library and add the reference (import the library) to your project.</li>
<li>Open the source file in C#</li>
<li>Use the `PutConvertWorkbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>NET Framework 4.5.2 or newer</li>
<li>Net Standard 2.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
