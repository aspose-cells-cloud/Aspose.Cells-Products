---
title: 使用 Java 将 SXC 转换为 SQL
description: 利用Aspose.Cells Cloud SDK for Java将SXC格式文件转换为SQL格式文件。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="将 SXC 转换为 SQL" h2="Java 用于将 SXC 转换为 SQL 的库" p="使用 Cells 云的转换 API 在 Java 项目中创建自定义电子表格工作流程。这是使用 Java 在线将 SXC 转换为 SQL 和其他文档格式的专业解决方案。" urlsection="conversion/sxc-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="使用 Cells Cloud SDK 将 SXC 转换为 SQL for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 SXC 转换为 SQL 可能是一项复杂的任务。我们的 Java SDK 处理所有 SXC 到 SQL 格式的转换，同时保留源 SXC 电子表格的主要结构和逻辑内容。我们的 Java 库提供了在线将 SXC 转换为 SQL 文件的专业解决方案。该Cloud SDK为Java开发者提供强大的功能，并保证高质量的SQL输出。
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java 使用 Cells Cloud SDK 将 SXC 转换为 SQL 的代码示例" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.sxc";
            String format = "sql";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.sql";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Java将Excel文件转换为其他格式SXC转SQL" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `putConvertWorkbook` 方法检索结果流。</li>
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
