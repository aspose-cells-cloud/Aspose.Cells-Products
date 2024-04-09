---
title: 使用 Cells Cloud SDK for NodeJS 将 Excel 中的 CHART 导出为 JPG
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="将 Excel 中的图表导出为 JPG" h2="用于将图表导出为 JPG 文件的 NodeJS 库" p="使用Cells云的Export API导出NodeJS中的Excel文件内部对象工作流程。这是使用 NodeJS 将电子表格在线导出 CHART 为 JPG 格式文件的专业解决方案。" urlsection="export/chart-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用Cells Cloud SDK for NodeJS将CHART对象导出为JPG格式文件" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 CHART 对象从 Excel 文件导出到 JPG 文件是一项复杂的任务。将 CHART 导出为 JPG 格式转换由我们的 NodeJS SDK 执行，同时保留源 CHART 电子表格的主要结构和逻辑内容。我们的 NodeJS 库是在线将 CHART 对象导出为 JPG 格式文件的专业解决方案。该Cloud SDK为NodeJS开发人员提供了强大的功能和完美的JPG输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="NodeJS 中使用 REST API 将电子表格中的图表导出为 JPG 格式的代码示例" gistPath="" %}}
  
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
      objectType : "chart",
      format: "jpg",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Node将Excel CHART中的对象导出为JPG" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `postExport` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>节点 v6.17.1 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
