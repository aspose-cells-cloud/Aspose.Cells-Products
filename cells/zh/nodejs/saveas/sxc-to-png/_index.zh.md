---
title: 使用 NodeJS 将 SXC 保存为 PNG
description: 利用Aspose.Cells Cloud SDK for NodeJS将SXC格式文件保存为PNG格式文件。
kwords: Excel, Save SXC as PNG, REST, NodeJS
howto: How to save SXC as PNG using Aspose.Cells Cloud NodeJS library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将SXC另存为PNG" h2="用于将 SXC 保存为 PNG 的 NodeJS 库" p="使用 Cells Cloud 的 SaveAs API 在 NodeJS 中创建自定义电子表格工作流程。这是使用NodeJS在线将SXC保存为PNG等文档格式的专业解决方案。" urlsection="saveas/sxc-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="在 NodeJS 中将 SXC 文件保存为 PNG" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 SXC 中的文件格式保存为 PNG 是一项复杂的任务。所有 SXC 到 PNG 的格式转换均由我们的 NodeJS SDK 执行，同时保留源 SXC 电子表格的主要结构和逻辑内容。我们的 NodeJS 库是在线将 SXC 保存为 PNG 文件的专业解决方案。该Cloud SDK为NodeJS开发人员提供了强大的功能和完美的PNG输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 REST API 将 SXC 保存为 PNG 的 NodeJS 代码示例" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.sxc",
      folder: "CellsTests",
      newfilename: "Book1Saveas.png",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud NodeJS 库将 SXC 另存为 PNG。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 NodeJS 库并将引用（导入库）添加到您的项目中。</li>
<li>在 JavaScript 中打开源文件。</li>
<li>使用 `PostWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>节点 v6.17.1 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
