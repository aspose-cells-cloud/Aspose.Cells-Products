﻿---
title: 数字到 PNG 将 API 转换为 C#
description: 用于 Microsoft Excel 和 OpenOffice Calc 的云 API 和 SDK。将电子表格转换为其他格式文件。
url: /zh/net/conversion/numbers-to-png/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API 将数字转换为 PNG" h2="C# 将数字转换为 PNG 的库" p="使用 Cells 转换 REST API 在 Net 中创建自定义电子表格工作流。这是使用 C# 在线将 NUMBERS 转换为 PNG 和其他文档格式的专业解决方案。" urlsection="conversion/numbers-to-png/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 NUMBERS 文件转换为 C# 中的 PNG" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 NUMBERS 转换为 PNG 是一项复杂的任务。所有 NUMBERS 到 PNG 的格式转换都由我们的 C# SDK 执行，同时保持源 NUMBERS 电子表格的主要结构和逻辑内容。我们的 C# 库是将数字在线转换为 PNG 文件的专业解决方案。此 Cloud SDK 为 C# 开发人员提供了强大的功能和完美的 PNG 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# 中的代码示例使用 REST API 将数字转换为 PNG 格式" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string format = "png";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.png";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 C# API 将 NUMBERS 转换为 PNG" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获得免费的 API 配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 CellsWorkbookPutConvertWorkbook 方法获取结果流</li>
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