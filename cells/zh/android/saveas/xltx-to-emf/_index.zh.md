---
title: 使用 Android 将 XLTX 保存为 EMF
description: 利用Aspose.Cells Cloud SDK for Android将XLTX格式文件保存为EMF格式文件。
kwords: Excel, Save XLTX as EMF, REST, Android
howto: How to save XLTX as EMF using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将XLTX另存为EMF" h2="用于将 XLTX 保存为 EMF 的 Android 库" p="使用 Cells Cloud 的 SaveAs API 在 Android 中创建自定义电子表格工作流程。这是使用Android在线将XLTX保存为EMF等文档格式的专业解决方案。" urlsection="saveas/xltx-to-emf/" >}}

{{< blocks/products/cells/cells-cloud-section title="在 Android 中将 XLTX 文件另存为 EMF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLTX 中的文件格式保存为 EMF 是一项复杂的任务。所有 XLTX 到 EMF 的格式转换均由我们的 Android SDK 执行，同时保留源 XLTX 电子表格的主要结构和逻辑内容。我们的 Android 库是在线将 XLTX 保存为 EMF 文件的专业解决方案。此Cloud SDK为Android开发者提供了强大的功能和完美的EMF输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 REST API 将 XLTX 保存为 EMF 的 Android 代码示例" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xltx";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.emf";
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
