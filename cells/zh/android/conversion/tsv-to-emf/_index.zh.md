---
title:  TSV 至 EMF 转换 API 适用于 Android
description: 使用Aspose.Cells Cloud SDK for Android将TSV格式文件转换为EMF格式文件。
url: /zh/android/conversion/tsv-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API 将 TSV 转换为 EMF" h2="将 TSV 转换为 EMF 的 Android 库" p="使用 Cells Conversion REST API 在 Android 中创建自定义电子表格工作流程。这是使用 Android 在线将 TSV 转换为 EMF 和其他文档格式的专业解决方案。" urlsection="conversion/tsv-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="在 Android 中将 TSV 文件转换为 EMF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 TSV 转换为 EMF 是一项复杂的任务。所有 TSV 到 EMF 格式的转换均由我们的 Android SDK 执行，同时保留源 TSV 电子表格的主要结构和逻辑内容。我们的 Android 库是在线将 TSV 转换为 EMF 文件的专业解决方案。此Cloud SDK为Android开发者提供了强大的功能和完美的EMF输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Android 中使用 REST API 将 TSV 转换为 EMF 格式的代码示例" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.tsv";
                String format = "emf";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.emf";
                try {
                    CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
                    File response = cellsApi.cellsWorkbookPutConvertWorkbook(new File(name), format, password, outPath, null,null);            
                    if(response.canRead())
                    {
                        if(response.exists()){
                            response.renameTo(new File(destFile));
                        }                
                    }
                }
                catch(Exception exception )
                {
                    System.out.print(exception);
                }
            }
        }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Java API 将 TSV 转换为 EMF" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 cellsWorkbookPutConvertWorkbook 方法来获取结果流</li>
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
