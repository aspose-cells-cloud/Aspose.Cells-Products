---
title: 使用 C# 将 PNG 保存为 TIFF
description: 利用Aspose.Cells Cloud SDK for C#将PNG格式文件保存为TIFF格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 PNG 另存为 TIFF" h2="C# 库，用于将 PNG 保存为 TIFF" p="使用 Cells Cloud 的 SaveAs API 在 Net 中创建自定义电子表格工作流程。这是使用C#在线将PNG另存为TIFF等文档格式的专业解决方案。" urlsection="saveas/png-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 PNG 文件另存为 C# 中的 TIFF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将文件格式从 PNG 保存为 TIFF 是一项复杂的任务。所有 PNG 到 TIFF 格式转换均由我们的 C# SDK 执行，同时保留源 PNG 电子表格的主要结构和逻辑内容。我们的 C# 库是在线将 PNG 保存为 TIFF 文件的专业解决方案。此Cloud SDK为C#开发者提供了强大的功能和完美的TIFF输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# 使用 REST API 将 PNG 保存为 TIFF 的代码示例" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.png";
    string newfilename = "Book1SaveAs.tiff";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Net将Excel文件保存为其他格式PNG为TIFF" >}}
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
