﻿---
title: 使用 Android 将 XML 保存为 XLSX
description: 利用Aspose.Cells Cloud SDK for Android将XML格式文件保存为XLSX格式文件。
kwords: Excel, Save XML as XLSX, REST, Android
howto: How to save XML as XLSX using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XML 保存为 XLSX" h2="用于将 XML 保存为 XLSX 的 Android 库" p="使用 Cells Cloud 的 SaveAs API 在 Android 中创建自定义电子表格工作流程。这是使用 Android 在线将 XML 保存为 XLSX 和其他文档格式的专业解决方案。" urlsection="saveas/xml-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section title="在 Android 中将 XML 文件另存为 XLSX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XML 文件格式保存为 XLSX 是一项复杂的任务。所有 XML 到 XLSX 格式的转换均由我们的 Android SDK 执行，同时保留源 XML 电子表格的主要结构和逻辑内容。我们的 Android 库是在线将 XML 保存为 XLSX 文件的专业解决方案。此 Cloud SDK 为 Android 开发人员提供了强大的功能和完美的 XLSX 输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 REST 将 XML 保存为 XLSX 的 Android 代码示例 API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xml";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xlsx";
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
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Android将Excel文件保存为其他格式" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `postWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Android 7 或更高版本</li>
<li>Java(TM) SE 运行时环境</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
