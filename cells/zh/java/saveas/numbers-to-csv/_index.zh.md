---
title: 使用 Java 将 NUMBERS 保存为 CSV
description: 利用Aspose.Cells Cloud SDK for Java将NUMBERS格式文件保存为CSV格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将数字另存为 CSV" h2="Java 用于将 NUMBERS 保存为 CSV 的库" p="使用 Cells Cloud 的 SaveAs API 在 Java 中创建自定义电子表格工作流程。这是使用 Java 在线将 NUMBERS 保存为 CSV 和其他文档格式的专业解决方案。" urlsection="saveas/numbers-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 NUMBERS 文件另存为 CSV 中的 Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 NUMBERS 文件格式保存为 CSV 是一项复杂的任务。所有 NUMBERS 到 CSV 格式的转换均由我们的 Java SDK 执行，同时保留源 NUMBERS 电子表格的主要结构和逻辑内容。我们的 Java 库是一个将数字在线保存为 CSV 文件的专业解决方案。该Cloud SDK为Java开发人员提供了强大的功能和完美的CSV输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java 使用 REST 将 NUMBERS 保存为 CSV 的代码示例 API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.numbers";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.csv";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Java将Excel文件保存为其他格式NUMBERS为CSV" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `postWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Maven 2.2.0 或更高版本</li>
<li>Java(TM) SE 运行时环境</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
