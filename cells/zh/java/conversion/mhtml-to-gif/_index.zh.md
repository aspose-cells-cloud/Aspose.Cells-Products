---
title: MHTML 到 GIF 转换 API for Java
description: 使用Aspose.Cells Cloud SDK for Java将MHTML格式文件转换为GIF格式文件。
url: /zh/java/conversion/mhtml-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API 将 MHTML 转换为 GIF" h2="Java 将 MHTML 转换为 GIF 的库" p="使用Cells转换REST API在Java中创建自定义电子表格工作流程。这是使用Java在线将MHTML转换为GIF和其他文档格式的专业解决方案。" urlsection="conversion/mhtml-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="将 MHTML 文件转换为 Java 中的 GIF" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 MHTML 转换为 GIF 是一项复杂的任务。所有 MHTML 到 GIF 格式的转换均由我们的 Java SDK 执行，同时保留源 MHTML 电子表格的主要结构和逻辑内容。我们的 Java 库是在线将 MHTML 转换为 GIF 文件的专业解决方案。该Cloud SDK为Java开发者提供了强大的功能和完美的GIF输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java中的代码示例使用REST API将MHTML转换为GIF格式" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.mhtml";
            String format = "gif";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.gif";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Java API 将 MHTML 转换为 GIF" >}}
<li>创建一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用客户端 ID、客户端密码、基本 URL 和 API 版本初始化 CellsApi</li>
<li>调用 cellsWorkbookPutConvertWorkbook 方法来获取结果流</li>
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
