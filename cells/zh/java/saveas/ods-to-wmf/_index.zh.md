---
title: 使用 Java 将 ODS 保存为 WMF
description: 利用Aspose.Cells Cloud SDK for Java将ODS格式文件保存为WMF格式文件。
kwords: Excel, Save ODS as WMF, REST, Java
howto: How to save ODS as WMF using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 ODS 保存为 WMF" h2="Java 用于将 ODS 保存为 WMF 的库" p="使用Cells云的SaveAs API在Java中创建自定义电子表格工作流程。这是使用Java在线将ODS保存为WMF和其他文档格式的专业解决方案。" urlsection="saveas/ods-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="将 ODS 文件另存为 WMF Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 ODS 中的文件格式保存为 WMF 是一项复杂的任务。所有 ODS 到 WMF 格式的转换均由我们的 Java SDK 执行，同时保留源 ODS 电子表格的主要结构和逻辑内容。我们的 Java 库是在线将 ODS 保存为 WMF 文件的专业解决方案。该Cloud SDK为Java开发人员提供了强大的功能和完美的WMF输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java 使用 REST 将 ODS 保存为 WMF 的代码示例 API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.ods";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.wmf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Java 库将 ODS 保存为 WMF。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Java 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Java中的源文件。</li>
<li>使用 `postWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Maven 2.2.0 或更高版本</li>
<li>Java(TM) SE 运行时环境</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
