---
title: 使用 Cells Cloud SDK for NodeJS 将 SHAPE 从 Excel 导出到 SVG
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
kwords: Excel, shape, svg, NodeJS
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Node to export objects from Excel SHAPE to SVG","description": "How to use Cells Cloud SDK for Node to export objects from Excel SHAPE to SVG","image": {"@type": "ImageObject"},"url": "/nodejs/export/shape-to-svg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel SHAPE to SVG step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/shape-to-svg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel SHAPE to SVG step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/shape-to-svg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Node to export objects from Excel SHAPE to SVG step 1", "image": {"@type": "ImageObject",},"url": "/nodejs/export/shape-to-svg/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, WebStorm"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 SHAPE 从 Excel 导出到 SVG" h2="用于将 SHAPE 导出到 SVG 文件的 NodeJS 库" p="使用Cells云的Export API导出NodeJS中的Excel文件内部对象工作流程。这是使用 NodeJS 将电子表格在线导出 SHAPE 为 SVG 格式文件的专业解决方案。" urlsection="export/shape-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for NodeJS 将 SHAPE 对象导出为 SVG 格式文件" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 SHAPE 对象从 Excel 文件导出到 SVG 文件是一项复杂的任务。将 SHAPE 导出到 SVG 格式转换由我们的 NodeJS SDK 执行，同时保留源 SHAPE 电子表格的主要结构和逻辑内容。我们的 NodeJS 库是在线将 SHAPE 对象导出为 SVG 格式文件的专业解决方案。该Cloud SDK为NodeJS开发人员提供了强大的功能和完美的SVG输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="NodeJS 中使用 REST API 将电子表格中的 SHAPE 导出为 SVG 格式的代码示例" gistPath="" %}}
  
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
      objectType : "shape",
      format: "svg",
    });
    cellsApi.postExport(req)
      .then((result) => {
        let buff = new Buffer(result.body.files[0].fileContent, 'base64');
        fs.writeFileSync(result.body.files[0].filename, buff);
    });
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Node将对象从Excel SHAPE导出到SVG" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `postExport` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>节点 v6.17.1 或更高版本</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
