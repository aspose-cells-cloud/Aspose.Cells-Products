---
title: 使用 Cells Cloud SDK for C# 将 WORKBOOK 从 Excel 导出为 JSON
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="将 WORKBOOK 从 Excel 导出为 JSON" h2="C# 用于将 WORKBOOK 导出到 JSON 文件的库" p="使用Cells云的导出API导出Net中的Excel文件内部对象工作流程。这是使用 C# 将电子表格在线导出 WORKBOOK 到 JSON 格式文件的专业解决方案。" urlsection="export/workbook-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for C# 将 WORKBOOK 对象导出为 JSON 格式文件" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 WORKBOOK 对象从 Excel 文件导出到 JSON 文件是一项复杂的任务。将 WORKBOOK 导出到 JSON 格式的转换由我们的 C# SDK 执行，同时保留源 WORKBOOK 电子表格的主要结构和逻辑内容。我们的 C# 库是在线将 WORKBOOK 对象导出为 JSON 格式文件的专业解决方案。该Cloud SDK为C#开发者提供了强大的功能和完美的JSON输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# 中的代码示例使用 REST API 将电子表格中的 WORKBOOK 导出为 JSON 格式" gistPath="" %}}
  
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
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Net将Excel WORKBOOK中的对象导出为JSON" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `postExport` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>NET Framework 4.5.2 或更高版本</li>
<li>网络标准 2.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
