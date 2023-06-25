---
title:  TXT 转 XPS 将 API 转换为 C#
description: 使用Aspose.Cells Cloud SDK for C#将TXT格式文件转换为XPS格式文件。
url: /zh/net/conversion/txt-to-xps/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="C# API 将 TXT 转换为 XPS" h2="C#库将TXT转换为XPS" p="使用 Cells Conversion REST API 在 Net 中创建自定义电子表格工作流程。这是使用C#在线将TXT转换为XPS和其他文档格式的专业解决方案。" urlsection="conversion/txt-to-xps/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将TXT文件转换为C#中的XPS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 TXT 转换为 XPS 是一项复杂的任务。所有 TXT 到 XPS 格式的转换均由我们的 C# SDK 执行，同时保留源 TXT 电子表格的主要结构和逻辑内容。我们的 C# 库是在线将 TXT 转换为 XPS 文件的专业解决方案。此Cloud SDK为C#开发者提供了强大的功能和完美的XPS输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="C#中的代码示例使用REST API将TXT转换为XPS格式" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.txt";
    string format = "xps";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xps";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 C# API 将 TXT 转换为 XPS" >}}
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
