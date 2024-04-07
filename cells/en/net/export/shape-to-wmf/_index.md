---
title: Export SHAPE to WMF from Excel using Cells Cloud SDK for C#  
description: Aspose.Cells Cloud REST API support exporting {0} to {1} format files using {2}. 
kwords: 
howto: 
---


{{< blocks/products/cells/cells-cloud-banner h1="Export SHAPE to WMF from Excel" h2="C# library for exporting SHAPE to WMF file" p="Use Export API of Cells Cloud to export Excel file internal object workflows in Net. This is a professional solution to export SHAPE to WMF format file from spreadsheet online using C#." urlsection="export/shape-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Export SHAPE object to WMF format file using Cells Cloud SDK for C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST %}}
<br/>
Export SHAPE object to WMF file from Excel file is a complex task. Export SHAPE to WMF format transitions is performed by our C# SDK while maintaining the source SHAPE spreadsheet's main structural and logical content. Our C# library is a professional solution to export SHAPE objects to WMF format files online. This Cloud SDK gives C# developers powerful functionality and perfect WMF output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Code example in C# using REST API to export SHAPE to WMF format from spreadsheet" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string format = "wmf";
    string objectType ="shape";
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
   
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Net to export objects from Excel SHAPE to WMF" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Use the `postExport` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>NET Framework 4.5.2 or newer</li>
<li>Net Standard 2.0 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
