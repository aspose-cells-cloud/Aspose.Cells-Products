---
title: 使用 C# 将 XLSX 保存为 MHTML
description: 利用Aspose.Cells Cloud SDK for C#将XLSX格式文件保存为MHTML格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 XLSX 保存为 MHTML" h2="C# 用于将 XLSX 保存为 MHTML 的库" p="使用 Cells Cloud 的 SaveAs API 在 Net 中创建自定义电子表格工作流程。这是使用 C# 在线将 XLSX 保存为 MHTML 和其他文档格式的专业解决方案。" urlsection="saveas/xlsx-to-mhtml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 C# 中将 XLSX 文件另存为 MHTML" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLSX 文件格式另存为 MHTML 是一项复杂的任务。所有 XLSX 到 MHTML 格式的转换均由我们的 C# SDK 执行，同时保留源 XLSX 电子表格的主要结构和逻辑内容。我们的 C# 库是在线将 XLSX 保存为 MHTML 文件的专业解决方案。该Cloud SDK为C#开发人员提供了强大的功能和完美的MHTML输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# 使用 REST 将 XLSX 保存为 MHTML 的代码示例 API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsx";
    string newfilename = "Book1SaveAs.mhtml";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Net将Excel文件保存为其他格式XLSX为MHTML" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `PostWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>NET Framework 4.5.2 或更高版本</li>
<li>网络标准 2.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
