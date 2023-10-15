---
title: 使用 NodeJS 将 XLSX 保存为 XLTM
description: 利用Aspose.Cells Cloud SDK for NodeJS将XLSX格式文件保存为XLTM格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 XLSX 保存为 XLTM" h2="用于将 XLSX 保存为 XLTM 的 NodeJS 库" p="使用 Cells Cloud 的 SaveAs API 在 NodeJS 中创建自定义电子表格工作流程。这是使用 NodeJS 在线将 XLSX 保存为 XLTM 等文档格式的专业解决方案。" urlsection="saveas/xlsx-to-xltm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 NodeJS 中将 XLSX 文件保存为 XLTM" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将文件格式从 XLSX 保存为 XLTM 是一项复杂的任务。所有 XLSX 到 XLTM 格式的转换均由我们的 NodeJS SDK 执行，同时保留源 XLSX 电子表格的主要结构和逻辑内容。我们的 NodeJS 库是在线将 XLSX 保存为 XLTM 文件的专业解决方案。该 Cloud SDK 为 NodeJS 开发人员提供了强大的功能和完美的 XLTM 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="使用 REST 将 XLSX 保存为 XLTM 的 NodeJS 代码示例 API" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { CellsApi, CellsSaveAs_PostDocumentSaveAsRequest } = require("asposecellscloud");
    const cellsApi = new CellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    var req = new CellsSaveAs_PostDocumentSaveAsRequest({
      name: "Book1.xlsx",
      folder: "CellsTests",
      newfilename: "Book1Saveas.xltm",
    });
    cellsApi.cellsSaveAsPostDocumentSaveAs(req)
      .then((result) => {
        console.log(result)
    });
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Node将Excel文件保存为其他格式XLSX为XLTM" >}}
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
