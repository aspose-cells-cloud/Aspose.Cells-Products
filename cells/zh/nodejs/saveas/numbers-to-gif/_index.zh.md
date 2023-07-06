---
title: 将数字另存为 GIF API 用于 NodeJS
description: 使用Aspose.Cells Cloud SDK for NodeJS将NUMBERS格式文件保存为GIF格式文件。
url: /zh/nodejs/saveas/numbers-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API 将 NUMBERS 保存为 GIF" h2="NodeJS 库将 NUMBERS 保存为 GIF" p="使用 Cells SaveAs REST API 在 NodeJS 中创建自定义电子表格工作流程。这是使用 NodeJS 在线将 NUMBERS 保存为 GIF 和其他文档格式的专业解决方案。" urlsection="saveas/numbers-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 NodeJS 中将 NUMBERS 文件另存为 GIF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 NUMBERS 文件格式保存为 GIF 是一项复杂的任务。所有 NUMBERS 到 GIF 格式的转换均由我们的 NodeJS SDK 执行，同时保留源 NUMBERS 电子表格的主要结构和逻辑内容。我们的 NodeJS 库是一个将数字在线保存为 GIF 文件的专业解决方案。该Cloud SDK为NodeJS开发人员提供了强大的功能和完美的GIF输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="NodeJS 中使用 REST API 将 NUMBERS 保存为 GIF 格式的代码示例" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.numbers",
      folder: "CellsTests",
      newfilename: "Book1Saveas.gif",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用节点API将NUMBERS保存为GIF" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 cellsSaveAsPostDocumentSaveAs 方法来获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>节点 v6.17.1 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
