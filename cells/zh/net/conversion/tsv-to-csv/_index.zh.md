﻿---
title: 使用 C# 将 TSV 转换为 CSV
description: 使用C#的Aspose.Cells Cloud SDK将TSV格式文件转换为CSV格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 TSV 转换为 CSV" h2="C# 用于将 TSV 转换为 CSV 的库" p="使用 Cells Cloud 的转换 API 在 Net 项目中创建自定义电子表格工作流。这是一个专业的解决方案，可使用 C# 在线将 TSV 转换为 CSV 和其他文档格式。" urlsection="conversion/tsv-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="使用 Cells Cloud SDK 将 C# 的 TSV 转换为 CSV" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 TSV 转换为 CSV 可能是一项复杂的任务。我们的 C# SDK 处理所有 TSV 到 CSV 格式的转换，同时保留源 TSV 电子表格的主要结构和逻辑内容。我们的 C# 库提供了在线将 TSV 转换为 CSV 文件的专业解决方案。该Cloud SDK为C#开发者提供了强大的功能，并确保高质量的CSV输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# 使用 Cells Cloud SDK 将 TSV 转换为 CSV 的代码示例" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.tsv";
    string format = "csv";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.csv";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells Cloud SDK for Net 将 Excel 文件转换为其他格式 TSV 到 CSV" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `PutConvertWorkbook` 方法检索结果流。</li>
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
