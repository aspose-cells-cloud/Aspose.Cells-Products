---
title: 将 XLSB 保存为 CSV API for Java
description: 使用Aspose.Cells Cloud SDK for Java将XLSB格式文件另存为CSV格式文件。
url: /zh/java/saveas/xlsb-to-csv/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API 将 XLSB 保存为 CSV" h2="Java 将 XLSB 保存为 CSV 的库" p="使用 Cells SaveAs REST API 在 Java 中创建自定义电子表格工作流程。这是使用 Java 在线将 XLSB 保存为 CSV 和其他文档格式的专业解决方案。" urlsection="saveas/xlsb-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 XLSB 文件另存为 CSV 中的 Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLSB 中的文件格式保存为 CSV 是一项复杂的任务。所有 XLSB 到 CSV 格式的转换均由我们的 Java SDK 执行，同时保留源 XLSB 电子表格的主要结构和逻辑内容。我们的 Java 库是在线将 XLSB 保存为 CSV 文件的专业解决方案。该Cloud SDK为Java开发人员提供了强大的功能和完美的CSV输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java 中的代码示例使用 REST API 将 XLSB 保存为 CSV 格式" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xlsb";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Java API 将 XLSB 保存为 CSV" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 cellsSaveAsPostDocumentSaveAs 方法来获取结果流</li>
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
