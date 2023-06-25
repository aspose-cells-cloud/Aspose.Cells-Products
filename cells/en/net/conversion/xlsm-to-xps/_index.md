---
title: XLSM to XPS Convert API for C# 
description: Using Aspose.Cells Cloud SDK for C# to convert XLSM format file to XPS format file. 
url: /net/conversion/xlsm-to-xps/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API to convert XLSM to XPS" h2="C# library to convert XLSM to XPS" p="Use Cells Conversion REST API to create customized spreadsheet workflows in Net. This is a professional solution to convert XLSM to XPS and other document formats online using C#." urlsection="conversion/xlsm-to-xps/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert a XLSM file to XPS in C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XLSM to XPS is a complex task. All XLSM to XPS format transitions is performed by our C# SDK while maintaining the source XLSM spreadsheet's main structural and logical content. Our C# library is a professional solution to convert XLSM to XPS files online. This Cloud SDK gives C# developers powerful functionality and perfect XPS output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in C# using REST API to convert XLSM to XPS format" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsm";
    string format = "xps";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xps";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use C# API to convert  XLSM to XPS" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call CellsWorkbookPutConvertWorkbook method to get the resultant stream</li>
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
