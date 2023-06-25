---
title: 将 MHTML 保存为 NodeJS 的 BMP API
description: 使用Aspose.Cells Cloud SDK for NodeJS将MHTML格式文件保存为BMP格式文件。
url: /zh/nodejs/saveas/mhtml-to-bmp/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="NodeJS API 将 MHTML 保存为 BMP" h2="NodeJS 库将 MHTML 保存为 BMP" p="使用 Cells SaveAs REST API 在 NodeJS 中创建自定义电子表格工作流程。这是使用 NodeJS 在线将 MHTML 保存为 BMP 等文档格式的专业解决方案。" urlsection="saveas/mhtml-to-bmp/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 NodeJS 中将 MHTML 文件另存为 BMP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 MHTML 文件格式保存为 BMP 是一项复杂的任务。所有 MHTML 到 BMP 格式的转换均由我们的 NodeJS SDK 执行，同时保留源 MHTML 电子表格的主要结构和逻辑内容。我们的 NodeJS 库是在线将 MHTML 保存为 BMP 文件的专业解决方案。该Cloud SDK为NodeJS开发人员提供了强大的功能和完美的BMP输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="NodeJS 中使用 REST API 将 MHTML 保存为 BMP 格式的代码示例" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.mhtml",
      folder: "CellsTests",
      newfilename: "Book1Saveas.bmp",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Node API将MHTML另存为BMP" >}}
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
