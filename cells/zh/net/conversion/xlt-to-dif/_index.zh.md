---
title:  XLT 到 DIF 将 API 转换为 C#
description: 使用Aspose.Cells Cloud SDK for C#将XLT格式文件转换为DIF格式文件。
url: /zh/net/conversion/xlt-to-dif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API 将 XLT 转换为 DIF" h2="C# 将 XLT 转换为 DIF 的库" p="使用 Cells Conversion REST API 在 Net 中创建自定义电子表格工作流程。这是使用 C# 在线将 XLT 转换为 DIF 和其他文档格式的专业解决方案。" urlsection="conversion/xlt-to-dif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 XLT 文件转换为 C# 中的 DIF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLT 转换为 DIF 是一项复杂的任务。所有 XLT 到 DIF 格式的转换均由我们的 C# SDK 执行，同时保留源 XLT 电子表格的主要结构和逻辑内容。我们的 C# 库是在线将 XLT 转换为 DIF 文件的专业解决方案。该Cloud SDK为C#开发者提供了强大的功能和完美的DIF输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C# 中的代码示例使用 REST API 将 XLT 转换为 DIF 格式" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlt";
    string format = "dif";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.dif";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 C# API 将 XLT 转换为 DIF" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 CellsWorkbookPutConvertWorkbook 方法获取结果流</li>
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
