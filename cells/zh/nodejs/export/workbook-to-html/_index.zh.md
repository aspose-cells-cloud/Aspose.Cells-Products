---
title: 使用 Cells Cloud SDK for NodeJS 将 WORKBOOK 从 Excel 导出到 HTML
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将工作簿从 Excel 导出到 HTML" h2="用于将 WORKBOOK 导出到 HTML 文件的 NodeJS 库" p="使用Cells云的Export API导出NodeJS中的Excel文件内部对象工作流程。这是使用 NodeJS 将电子表格在线导出 WORKBOOK 为 HTML 格式文件的专业解决方案。" urlsection="export/workbook-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="使用 Cells Cloud SDK for NodeJS 将 WORKBOOK 对象导出为 HTML 格式文件" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 WORKBOOK 对象从 Excel 文件导出到 HTML 文件是一项复杂的任务。将 WORKBOOK 导出到 HTML 格式转换由我们的 NodeJS SDK 执行，同时保留源 WORKBOOK 电子表格的主要结构和逻辑内容。我们的 NodeJS 库是在线将 WORKBOOK 对象导出为 HTML 格式文件的专业解决方案。该Cloud SDK为NodeJS开发人员提供了强大的功能和完美的HTML输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="NodeJS 中使用 REST API 将电子表格中的 WORKBOOK 导出为 HTML 格式的代码示例" gistPath="" %}}
  
```js
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-node/
    const { LightCellsApi, PostExportRequest } = require("asposecellscloud");
    const localPath = "C:/";
    var fs = require('fs');
    var path = require('path');
    const cellsApi = new LightCellsApi(process.env.ProductClientId, process.env.ProductClientSecret);
    const AssemblyTestXlsx = "assemblytest.xlsx";
    var dataAssemblyTestXlsx =fs.createReadStream(localPath  + AssemblyTestXlsx);
    const DataSourceXlsx = "datasource.xlsx";
    var dataDataSourceXlsx =fs.createReadStream(localPath  + DataSourceXlsx);
    var req = new PostExportRequest({
      file:{AssemblyTestXlsx:dataAssemblyTestXlsx ,DataSourceXlsx:dataDataSourceXlsx },
      objectType : "workbook",
      format: "html",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Node将Excel WORKBOOK中的对象导出到HTML" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `postExport` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>节点 v6.17.1 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
