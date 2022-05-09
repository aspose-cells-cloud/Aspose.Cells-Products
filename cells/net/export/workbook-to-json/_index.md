---
title: Export Workbook to JSON file via .NET
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Export workbok or interanl object to kinds of format file in the Cloud.
url: /net/export/workbook-to-json/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Export Workbook to JSON file in the Cloud" h2="Excel & OpenOffice spreadsheet export with open source Cloud SDK for .NET">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export Workbook to JSON file in Cloud SDK for .NET " %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```LightCellsAPI``` with Client Id, Client Secret, Base URL & API version
1. Call ```PostExport``` method to get the resultant JSON stream
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for .NET source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) to compile the SDK yourself or head to the [Releases](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/releases) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/#/LightCells/PostExport) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Net Code for WORKBOOK to JSON Conversion" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
string format = "json";
string objectType ="workbook";
LightCellsApi lightCellsApi =
    new LightCellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
IDictionary<string ,Stream> files = new  Dictionary<string ,Stream>();
files.Add("Book1.xlsx" , File.OpenRead("Book1.xlsx"));
files.Add("myDocument.xlsx", File.OpenRead("myDocument.xlsx"));
var filesResult = lightCellsApi.PostExport(files, objectType, format);
foreach (var file in filesResult.Files)
{
    string v = file.FileContent;
    string filename = file.Filename;
    byte[] workbookData = System.Convert.FromBase64String(v);
    MemoryStream memoryStream = new MemoryStream(workbookData, 0, workbookData.Length);
    memoryStream.Seek(0, SeekOrigin.Begin);
    using (FileStream fileStream = File.Create( filename))
    {
        fileStream.Position = 0;
        memoryStream.CopyTo(fileStream);
        fileStream.Close();
    }
}
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
