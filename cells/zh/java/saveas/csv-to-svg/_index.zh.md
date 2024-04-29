---
title: 使用 Java 将 CSV 保存为 SVG
description: 利用Aspose.Cells Cloud SDK for Java将CSV格式文件保存为SVG格式文件。
kwords: Excel, Save CSV as SVG, REST, Java
howto: "{"@context": "https://schema.org","@type": "HowTo","name": "How to save CSV as SVG using the Cells Cloud Java library.","description": "How to save CSV as SVG using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/saveas/csv-to-svg/","step": [{ "@type": "HowToStep","name": "How to save CSV as SVG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/csv-to-svg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save CSV as SVG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/csv-to-svg/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save CSV as SVG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/csv-to-svg/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to save CSV as SVG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/csv-to-svg/","text": "Use the `postWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}"
fqa: "{"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}"
---
{{< blocks/products/cells/cells-cloud-banner h1="将 CSV 保存为 SVG" h2="Java 用于将 CSV 保存为 SVG 的库" p="使用Cells云的SaveAs API在Java中创建自定义电子表格工作流程。这是使用Java在线将CSV保存为SVG和其他文档格式的专业解决方案。" urlsection="saveas/csv-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="将 CSV 文件另存为 Java 中的 SVG" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 CSV 文件格式保存为 SVG 是一项复杂的任务。所有 CSV 到 SVG 格式的转换均由我们的 Java SDK 执行，同时保留源 CSV 电子表格的主要结构和逻辑内容。我们的 Java 库是在线将 CSV 保存为 SVG 文件的专业解决方案。此Cloud SDK为Java开发者提供了强大的功能和完美的SVG输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java 使用 REST 将 CSV 保存为 SVG 的代码示例 API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.csv";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.svg";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells 云 Java 库将 CSV 保存为 SVG。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Java 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Java中的源文件。</li>
<li>使用 `postWorkbookSaveAs` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Maven 2.2.0 或更高版本</li>
<li>Java(TM) SE 运行时环境</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
