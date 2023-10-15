---
title: 使用 Java 将 JPG 保存为 BMP
description: 利用Aspose.Cells Cloud SDK for Java将JPG格式文件保存为BMP格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 JPG 保存为 BMP" h2="Java 用于将 JPG 保存为 BMP 的库" p="使用Cells云的另存为API在Java中创建自定义电子表格工作流程。这是使用Java在线将JPG保存为BMP和其他文档格式的专业解决方案。" urlsection="saveas/jpg-to-bmp/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将JPG文件另存为Java中的BMP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 JPG 文件格式保存为 BMP 是一项复杂的任务。所有 JPG 到 BMP 格式的转换均由我们的 Java SDK 执行，同时保留源 JPG 电子表格的主要结构和逻辑内容。我们的 Java 库是在线将 JPG 保存为 BMP 文件的专业解决方案。此Cloud SDK为Java开发者提供了强大的功能和完美的BMP输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java 使用 REST 将 JPG 保存为 BMP 的代码示例 API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.jpg";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.bmp";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells云SDK for Java将Excel文件保存为其他格式JPG为BMP" >}}
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
