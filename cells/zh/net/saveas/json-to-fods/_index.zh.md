﻿---
title: 将 JSON 保存为 C# 的 FODS API
description: 用于 Microsoft Excel 和 OpenOffice Calc 的云 API 和 SDK。将电子表格转换为其他格式文件。
url: /zh/net/saveas/json-to-fods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API 将JSON保存为FODS" h2="C# 将 JSON 保存为 FODS 的库" p="使用 Cells SaveAs REST API 在 Net 中创建自定义电子表格工作流程。这是使用C#在线将JSON保存为FODS等文档格式的专业解决方案。" urlsection="saveas/json-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 C# 中将 JSON 文件另存为 FODS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 JSON 中的文件格式保存为 FODS 是一项复杂的任务。所有 JSON 到 FODS 格式的转换都由我们的 C# SDK 执行，同时保持源 JSON 电子表格的主要结构和逻辑内容。我们的 C# 库是将 JSON 在线保存为 FODS 文件的专业解决方案。此 Cloud SDK 为 C# 开发人员提供了强大的功能和完美的 FODS 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# 中的代码示例使用 REST API 将 JSON 保存为 FODS 格式" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.json";
    string newfilename = "Book1SaveAs.fods";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用C# API将JSON保存为FODS" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获得免费的 API 配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 CellsSaveAsPostDocumentSaveAs 方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>NET Framework 4.5.2 或更新版本</li>
<li>网络标准 2.0 或更新版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}