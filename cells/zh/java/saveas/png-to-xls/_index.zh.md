---
title: 使用 Java 将 PNG 保存为 XLS
description: 利用Aspose.Cells Cloud SDK for Java将PNG格式文件保存为XLS格式文件。
kwords: Excel, Save PNG as XLS, REST, Java
howto: How to save PNG as XLS using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 PNG 另存为 XLS" h2="Java 库，用于将 PNG 保存为 XLS" p="使用Cells云的SaveAs API在Java中创建自定义电子表格工作流程。这是使用Java在线将PNG保存为XLS和其他文档格式的专业解决方案。" urlsection="saveas/png-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section title="将 PNG 文件另存为 Java 中的 XLS" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 PNG 中的文件格式保存为 XLS 是一项复杂的任务。所有 PNG 到 XLS 格式的转换均由我们的 Java SDK 执行，同时保留源 PNG 电子表格的主要结构和逻辑内容。我们的 Java 库是在线将 PNG 保存为 XLS 文件的专业解决方案。该Cloud SDK为Java开发人员提供了强大的功能和完美的XLS输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java 使用 REST API 将 PNG 保存为 XLS 的代码示例" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.png";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xls";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells 云 Java 库将 PNG 另存为 XLS。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Java 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Java中的源文件。</li>
<li>使用 `postWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Maven 2.2.0 或更高版本</li>
<li>Java(TM) SE 运行时环境</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
