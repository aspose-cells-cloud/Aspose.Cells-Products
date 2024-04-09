---
title: 使用 NodeJS 将 XLS 转换为 XLSB
description: 使用Aspose.Cells Cloud SDK for NodeJS将XLS格式文件转换为XLSB格式文件。
kwords: Excel, Convert XLS to XLSB, REST, NodeJS
howto: How to convert XLS to XLSB using Aspose.Cells Cloud NodeJS library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLS 转换为 XLSB" h2="用于将 XLS 转换为 XLSB 的 NodeJS 库" p="使用 Cells 云的转换 API 在 NodeJS 项目中创建自定义电子表格工作流程。这是使用 NodeJS 在线将 XLS 转换为 XLSB 等文档格式的专业解决方案。" urlsection="conversion/xls-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for NodeJS 将 XLS 转换为 XLSB" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLS 转换为 XLSB 可能是一项复杂的任务。我们的 NodeJS SDK 处理所有 XLS 到 XLSB 格式的转换，同时保留源 XLS 电子表格的主要结构和逻辑内容。我们的 NodeJS 库提供了在线将 XLS 转换为 XLSB 文件的专业解决方案。该Cloud SDK为NodeJS开发人员提供了强大的功能，并确保高质量的XLSB输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 Cells Cloud SDK 将 XLS 转换为 XLSB 的 NodeJS 代码示例" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.xls"),
        format: "xlsb",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud NodeJS 库将 XLS 转换为 XLSB。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 NodeJS 库并将引用（导入库）添加到您的项目中。</li>
<li>在 JavaScript 中打开源文件。</li>
<li>使用 `putConvertWorkbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>节点 v6.17.1 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
