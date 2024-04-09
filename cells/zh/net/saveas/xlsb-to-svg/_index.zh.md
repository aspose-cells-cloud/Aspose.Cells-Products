---
title: 使用 C# 将 XLSB 保存为 SVG
description: 利用Aspose.Cells Cloud SDK for C#将XLSB格式文件保存为SVG格式文件。
kwords: Excel, Save XLSB as SVG, REST, C#
howto: How to save XLSB as SVG using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将XLSB另存为SVG" h2="C# 用于将 XLSB 保存为 SVG 的库" p="使用 Cells Cloud 的 SaveAs API 在 Net 中创建自定义电子表格工作流程。这是使用C#在线将XLSB保存为SVG和其他文档格式的专业解决方案。" urlsection="saveas/xlsb-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="将 XLSB 文件另存为 C# 中的 SVG" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLSB 中的文件格式保存为 SVG 是一项复杂的任务。所有 XLSB 到 SVG 格式的转换均由我们的 C# SDK 执行，同时保留源 XLSB 电子表格的主要结构和逻辑内容。我们的 C# 库是在线将 XLSB 保存为 SVG 文件的专业解决方案。此Cloud SDK为C#开发者提供了强大的功能和完美的SVG输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# 使用 REST 将 XLSB 保存为 SVG 的代码示例 API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsb";
    string newfilename = "Book1SaveAs.svg";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Net 库将 XLSB 保存为 SVG。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 C# 库并将引用（导入库）添加到您的项目中。</li>
<li>打开C#中的源文件</li>
<li>使用 `PostWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>NET Framework 4.5.2 或更高版本</li>
<li>网络标准 2.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
