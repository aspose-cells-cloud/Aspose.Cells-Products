---
title: 使用 Java 将 NUMBERS 保存为 XLSM
description: 利用Aspose.Cells Cloud SDK for Java将NUMBERS格式文件保存为XLSM格式文件。
kwords: Excel, Save NUMBERS as XLSM, REST, Java
howto: How to save NUMBERS as XLSM using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 NUMBERS 保存为 XLSM" h2="Java 用于将 NUMBERS 保存为 XLSM 的库" p="使用Cells Cloud的SaveAs API在Java中创建自定义电子表格工作流程。这是使用Java在线将NUMBERS保存为XLSM和其他文档格式的专业解决方案。" urlsection="saveas/numbers-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section title="将 NUMBERS 文件另存为 XLSM，位于 Java 中" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 NUMBERS 文件格式保存为 XLSM 是一项复杂的任务。所有 NUMBERS 到 XLSM 格式的转换均由我们的 Java SDK 执行，同时保留源 NUMBERS 电子表格的主要结构和逻辑内容。我们的 Java 库是在线将数字保存为 XLSM 文件的专业解决方案。该Cloud SDK为Java开发人员提供了强大的功能和完美的XLSM输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java 使用 REST 将 NUMBERS 保存为 XLSM 的代码示例 API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.numbers";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xlsm";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="了解如何使用 Cells Cloud Java 库将 NUMBERS 保存为 XLSM。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Java 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Java中的源文件。</li>
<li>使用 `postWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Maven 2.2.0 或更高版本</li>
<li>Java(TM) SE 运行时环境</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
