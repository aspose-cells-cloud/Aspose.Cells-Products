---
title: 使用 C# 将 XLSM 转换为 TXT
description: 利用C#的Aspose.Cells Cloud SDK将XLSM格式文件转换为TXT格式文件。
kwords: Excel, Convert XLSM to TXT, REST, C#
howto: How to convert XLSM to TXT using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLSM 转换为 TXT" h2="C# 用于将 XLSM 转换为 TXT 的库" p="使用 Cells 云的转换 API 在 Net 项目中创建自定义电子表格工作流程。这是使用C#在线将XLSM转换为TXT等文档格式的专业解决方案。" urlsection="conversion/xlsm-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for C# 将 XLSM 转换为 TXT" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLSM 转换为 TXT 可能是一项复杂的任务。我们的 C# SDK 处理所有 XLSM 到 TXT 格式的转换，同时保留源 XLSM 电子表格的主要结构和逻辑内容。我们的 C# 库提供了在线将 XLSM 转换为 TXT 文件的专业解决方案。该Cloud SDK为C#开发者提供强大的功能，并保证高质量的TXT输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# 使用 Cells Cloud SDK 将 XLSM 转换为 TXT 的代码示例" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlsm";
    string format = "txt";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.txt";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Net 库将 XLSM 转换为 TXT。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 C# 库并将引用（导入库）添加到您的项目中。</li>
<li>打开C#中的源文件</li>
<li>使用 `PutConvertWorkbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>NET Framework 4.5.2 或更高版本</li>
<li>网络标准 2.0 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
