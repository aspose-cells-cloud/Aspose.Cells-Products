﻿---
title: 将 GIF 另存为 DOCX API for Java
description: 用于 Microsoft Excel 和 OpenOffice Calc 的云 API 和 SDK。将电子表格转换为其他格式文件。
url: /zh/java/saveas/gif-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API 将 GIF 保存为 DOCX" h2="Java 将 GIF 保存为 DOCX 的库" p="使用Cells SaveAs REST API在Java中创建自定义电子表格工作流程。这是使用Java在线将GIF保存为DOCX和其他文档格式的专业解决方案。" urlsection="saveas/gif-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Java 中将 GIF 文件另存为 DOCX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 GIF 文件格式保存为 DOCX 是一项复杂的任务。所有 GIF 到 DOCX 格式的转换都由我们的 Java SDK 执行，同时保持源 GIF 电子表格的主要结构和逻辑内容。我们的 Java 库是将 GIF 在线保存为 DOCX 文件的专业解决方案。此 Cloud SDK 为 Java 开发人员提供了强大的功能和完美的 DOCX 输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java 中的代码示例使用 REST API 将 GIF 保存为 DOCX 格式" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.gif";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.docx";
    String folder ="CellsTests";
    try 
    {
        CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
        cellsApi.cellsSaveAsPostDocumentSaveAs(name , saveOptions,newfilename,false,false,folder,null,null,null,true);                       
    }
    catch(Exception exception )
    {
        System.out.print(exception);
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Java API将GIF保存为DOCX" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获得免费的 API 配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 cellsSaveAsPostDocumentSaveAs 方法获取结果流</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Maven 2.2.0 或更新版本</li>
<li>Java(TM) SE 运行时环境</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}