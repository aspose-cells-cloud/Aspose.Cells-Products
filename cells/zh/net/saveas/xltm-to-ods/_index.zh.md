---
title: 将 XLTM 另存为 C# 的 ODS API
description: 使用Aspose.Cells Cloud SDK for C#将XLTM格式文件保存为ODS格式文件。
url: /zh/net/saveas/xltm-to-ods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API 将 XLTM 保存为 ODS" h2="C# 将 XLTM 保存为 ODS 的库" p="使用 Cells SaveAs REST API 在 Net 中创建自定义电子表格工作流程。这是使用 C# 在线将 XLTM 保存为 ODS 和其他文档格式的专业解决方案。" urlsection="saveas/xltm-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 XLTM 文件另存为 C# 中的 ODS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLTM 中的文件格式保存为 ODS 是一项复杂的任务。所有 XLTM 到 ODS 格式的转换均由我们的 C# SDK 执行，同时保留源 XLTM 电子表格的主要结构和逻辑内容。我们的 C# 库是将 XLTM 在线保存为 ODS 文件的专业解决方案。该Cloud SDK为C#开发者提供了强大的功能和完美的ODS输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# 中的代码示例使用 REST API 将 XLTM 保存为 ODS 格式" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xltm";
    string newfilename = "Book1SaveAs.ods";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用C# API将XLTM保存为ODS" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 CellsSaveAsPostDocumentSaveAs 方法获取结果流</li>
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
