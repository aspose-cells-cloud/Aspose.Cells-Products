---
title: 将 XLSM 另存为 Android 版 TXT API
description: 使用Aspose.Cells Cloud SDK for Android将XLSM格式文件保存为TXT格式文件。
url: /zh/android/saveas/xlsm-to-txt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API 将XLSM保存为TXT" h2="Android 库将 XLSM 保存为 TXT" p="使用 Cells SaveAs REST API 在 Android 中创建自定义电子表格工作流程。这是使用Android在线将XLSM保存为TXT和其他文档格式的专业解决方案。" urlsection="saveas/xlsm-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Android 中将 XLSM 文件另存为 TXT" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
将 XLSM 中的文件格式保存为 TXT 是一项复杂的任务。所有 XLSM 到 TXT 格式的转换均由我们的 Android SDK 执行，同时保留源 XLSM 电子表格的主要结构和逻辑内容。我们的 Android 库是在线将 XLSM 保存为 TXT 文件的专业解决方案。该Cloud SDK为Android开发者提供了强大的功能和完美的TXT输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Android 中使用 REST API 将 XLSM 保存为 TXT 格式的代码示例" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xlsm";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.txt";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Java API将XLSM另存为TXT" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 cellsSaveAsPostDocumentSaveAs 方法来获取结果流</li>
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
