﻿---
title: 使用 Android 将 ODS 转换为 BMP
description: 利用 Aspose.Cells Cloud SDK for Android 将 ODS 格式文件转换为 BMP 格式文件。
kwords: Excel, Convert ODS to BMP, REST, Android
howto: How to convert ODS to BMP using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="将 ODS 转换为 BMP" h2="用于将 ODS 转换为 BMP 的 Android 库" p="使用 Cells 云的转换 API 在 Android 项目中创建自定义电子表格工作流程。这是使用Android在线将ODS转换为BMP和其他文档格式的专业解决方案。" urlsection="conversion/ods-to-bmp/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Android 将 ODS 转换为 BMP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 ODS 转换为 BMP 可能是一项复杂的任务。我们的 Android SDK 处理所有 ODS 到 BMP 格式的转换，同时保留源 ODS 电子表格的主要结构和逻辑内容。我们的Android库提供了在线将ODS转换为BMP文件的专业解决方案。该Cloud SDK为Android开发者提供了强大的功能，并确保高质量的BMP输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="使用 Cells Cloud SDK 将 ODS 转换为 BMP 的 Android 代码示例" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.ods";
                String format = "bmp";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.bmp";
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
