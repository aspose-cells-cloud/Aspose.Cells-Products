---
title: 将XLTM另存为PPTX API for Java
description: 使用Aspose.Cells Cloud SDK for Java将XLTM格式文件另存为PPTX格式文件。
url: /zh/java/saveas/xltm-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API 将 XLTM 保存为 PPTX" h2="Java 将 XLTM 保存为 PPTX 的库" p="使用 Cells SaveAs REST API 在 Java 中创建自定义电子表格工作流程。这是使用 Java 在线将 XLTM 保存为 PPTX 和其他文档格式的专业解决方案。" urlsection="saveas/xltm-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Java 中将 XLTM 文件另存为 PPTX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLTM 中的文件格式另存为 PPTX 是一项复杂的任务。所有 XLTM 到 PPTX 格式的转换均由我们的 Java SDK 执行，同时保留源 XLTM 电子表格的主要结构和逻辑内容。我们的 Java 库是将 XLTM 在线保存为 PPTX 文件的专业解决方案。该Cloud SDK为Java开发者提供了强大的功能和完美的PPTX输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java 中的代码示例使用 REST API 将 XLTM 保存为 PPTX 格式" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xltm";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.pptx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Java API 将XLTM另存为PPTX" >}}
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
