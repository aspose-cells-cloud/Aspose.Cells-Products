---
title: 使用 NodeJS 将 XLTX 保存为 TIFF
description: 利用Aspose.Cells Cloud SDK for NodeJS将XLTX格式文件保存为TIFF格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将XLTX另存为TIFF" h2="用于将 XLTX 保存为 TIFF 的 NodeJS 库" p="使用 Cells Cloud 的 SaveAs API 在 NodeJS 中创建自定义电子表格工作流程。这是使用NodeJS在线将XLTX保存为TIFF等文档格式的专业解决方案。" urlsection="saveas/xltx-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 NodeJS 中将 XLTX 文件保存为 TIFF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLTX 中的文件格式保存为 TIFF 是一项复杂的任务。所有 XLTX 到 TIFF 的格式转换均由我们的 NodeJS SDK 执行，同时保留源 XLTX 电子表格的主要结构和逻辑内容。我们的 NodeJS 库是在线将 XLTX 保存为 TIFF 文件的专业解决方案。该Cloud SDK为NodeJS开发人员提供了强大的功能和完美的TIFF输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="使用 REST API 将 XLTX 保存为 TIFF 的 NodeJS 代码示例" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xltx",
      folder: "CellsTests",
      newfilename: "Book1Saveas.tiff",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Node将Excel文件保存为其他格式XLTX为TIFF" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `PostWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>节点 v6.17.1 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
