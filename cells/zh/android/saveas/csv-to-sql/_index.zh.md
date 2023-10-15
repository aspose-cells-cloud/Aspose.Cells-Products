---
title: 使用 Android 将 CSV 保存为 SQL
description: 利用Aspose.Cells Cloud SDK for Android将CSV格式文件保存为SQL格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 CSV 保存为 SQL" h2="用于将 CSV 保存为 SQL 的 Android 库" p="使用 Cells Cloud 的 SaveAs API 在 Android 中创建自定义电子表格工作流程。这是使用 Android 在线将 CSV 保存为 SQL 和其他文档格式的专业解决方案。" urlsection="saveas/csv-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Android 中将 CSV 文件另存为 SQL" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 CSV 文件格式保存为 SQL 是一项复杂的任务。所有 CSV 到 SQL 格式的转换均由我们的 Android SDK 执行，同时保留源 CSV 电子表格的主要结构和逻辑内容。我们的 Android 库是在线将 CSV 保存为 SQL 文件的专业解决方案。该Cloud SDK为Android开发者提供了强大的功能和完美的SQL输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="使用 REST 将 CSV 保存为 SQL 的 Android 代码示例 API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.csv";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.sql";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells Cloud SDK for Android 将 Excel 文件保存为其他格式 CSV as SQL" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `postWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Android 7 或更高版本</li>
<li>Java(TM) SE 运行时环境</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
