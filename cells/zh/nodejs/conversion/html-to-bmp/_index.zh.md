﻿---
title:  HTML 到 BMP 转换 API for NodeJS
description: 使用Aspose.Cells Cloud SDK for NodeJS将HTML格式文件转换为BMP格式文件。
url: /zh/nodejs/conversion/html-to-bmp/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API 将 HTML 转换为 BMP" h2="NodeJS 库将 HTML 转换为 BMP" p="使用 Cells Conversion REST API 在 NodeJS 中创建自定义电子表格工作流程。这是使用NodeJS在线将HTML转换为BMP等文档格式的专业解决方案。" urlsection="conversion/html-to-bmp/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 NodeJS 中将 HTML 文件转换为 BMP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 HTML 转换为 BMP 是一项复杂的任务。所有 HTML 到 BMP 格式转换均由我们的 NodeJS SDK 执行，同时保留源 HTML 电子表格的主要结构和逻辑内容。我们的 NodeJS 库是在线将 HTML 转换为 BMP 文件的专业解决方案。该Cloud SDK为NodeJS开发人员提供了强大的功能和完美的BMP输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="NodeJS 中使用 REST API 将 HTML 转换为 BMP 格式的代码示例" gistPath="" %}}
 
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsWorkbook_PutConvertWorkbookRequest } = require("asposecellscloud");
    const localPath = "../TestData/source/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsWorkbook_PutConvertWorkbookRequest({
        file: fs.createReadStream(localPath + "datasource.html"),
        format: "bmp",
    });
    cellsApi.cellsWorkbookPutConvertWorkbook(req)
        .then((result) => {
        console.log(result)
    });
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用节点API将HTML转换为BMP" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 cellsWorkbookPutConvertWorkbook 方法来获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>节点 v6.17.1 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
