---
title: 使用 NodeJS 将 PNG 转换为 TSV
description: 利用Aspose.Cells Cloud SDK for NodeJS将PNG格式文件转换为TSV格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 PNG 转换为 TSV" h2="用于将 PNG 转换为 TSV 的 NodeJS 库" p="使用 Cells 云的转换 API 在 NodeJS 项目中创建自定义电子表格工作流程。这是使用 NodeJS 在线将 PNG 转换为 TSV 和其他文档格式的专业解决方案。" urlsection="conversion/png-to-tsv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="使用 Cells Cloud SDK for NodeJS 将 PNG 转换为 TSV" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 PNG 转换为 TSV 可能是一项复杂的任务。我们的 NodeJS SDK 处理所有 PNG 到 TSV 格式的转换，同时保留源 PNG 电子表格的主要结构和逻辑内容。我们的 NodeJS 库提供了在线将 PNG 转换为 TSV 文件的专业解决方案。该Cloud SDK为NodeJS开发人员提供了强大的功能，并确保高质量的TSV输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="使用 Cells Cloud SDK 将 PNG 转换为 TSV 的 NodeJS 代码示例" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.png"),
        format: "tsv",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Node将Excel文件转换为其他格式PNG转TSV" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `putConvertWorkbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>节点 v6.17.1 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
