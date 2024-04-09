---
title: 使用 Android 将 XLSB 转换为 SQL
description: 利用Aspose.Cells Cloud SDK for Android将XLSB格式文件转换为SQL格式文件。
kwords: Excel, Convert XLSB to SQL, REST, Android
howto: How to convert XLSB to SQL using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLSB 转换为 SQL" h2="用于将 XLSB 转换为 SQL 的 Android 库" p="使用 Cells 云的转换 API 在 Android 项目中创建自定义电子表格工作流程。这是使用 Android 在线将 XLSB 转换为 SQL 和其他文档格式的专业解决方案。" urlsection="conversion/xlsb-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Android 将 XLSB 转换为 SQL" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLSB 转换为 SQL 可能是一项复杂的任务。我们的 Android SDK 处理所有 XLSB 到 SQL 格式的转换，同时保留源 XLSB 电子表格的主要结构和逻辑内容。我们的 Android 库提供了在线将 XLSB 转换为 SQL 文件的专业解决方案。该Cloud SDK为Android开发人员提供了强大的功能，并确保高质量的SQL输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 Cells Cloud SDK 将 XLSB 转换为 SQL 的 Android 代码示例" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xlsb";
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
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Android将Excel文件转换为其他格式" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `putConvertWorkbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Android 7 或更高版本</li>
<li>Java(TM) SE 运行时环境</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
