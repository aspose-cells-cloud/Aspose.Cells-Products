---
title: 使用 NodeJS 将 PNG 保存为 GIF
description: 利用Aspose.Cells Cloud SDK for NodeJS将PNG格式文件保存为GIF格式文件。
kwords: Excel, Save PNG as GIF, REST, NodeJS
howto: How to save PNG as GIF using Aspose.Cells Cloud NodeJS library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 PNG 另存为 GIF" h2="用于将 PNG 保存为 GIF 的 NodeJS 库" p="使用 Cells Cloud 的 SaveAs API 在 NodeJS 中创建自定义电子表格工作流程。这是使用NodeJS在线将PNG保存为GIF等文档格式的专业解决方案。" urlsection="saveas/png-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="在 NodeJS 中将 PNG 文件另存为 GIF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 PNG 中的文件格式保存为 GIF 是一项复杂的任务。所有 PNG 到 GIF 格式的转换均由我们的 NodeJS SDK 执行，同时保留源 PNG 电子表格的主要结构和逻辑内容。我们的 NodeJS 库是在线将 PNG 保存为 GIF 文件的专业解决方案。该Cloud SDK为NodeJS开发人员提供了强大的功能和完美的GIF输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 REST API 将 PNG 保存为 GIF 的 NodeJS 代码示例" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.png",
      folder: "CellsTests",
      newfilename: "Book1Saveas.gif",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud NodeJS 库将 PNG 另存为 GIF。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 NodeJS 库并将引用（导入库）添加到您的项目中。</li>
<li>在 JavaScript 中打开源文件。</li>
<li>使用 `PostWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>节点 v6.17.1 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
