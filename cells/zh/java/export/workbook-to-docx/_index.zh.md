---
title: 使用 Cells Cloud SDK for Java 将 WORKBOOK 从 Excel 导出到 DOCX
description:  Aspose.Cells Cloud REST API 支持使用 {2} 将 {0} 导出为 {1} 格式文件。
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="将 WORKBOOK 从 Excel 导出到 DOCX" h2="Java 用于将 WORKBOOK 导出到 DOCX 文件的库" p="使用Cells云的导出API导出Java中的Excel文件内部对象工作流程。这是使用Java在线将电子表格中的WORKBOOK导出为DOCX格式文件的专业解决方案。" urlsection="export/workbook-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK 将 WORKBOOK 对象导出为 DOCX 格式文件 for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
将 WORKBOOK 对象从 Excel 文件导出到 DOCX 文件是一项复杂的任务。将 WORKBOOK 导出为 DOCX 格式转换由我们的 Java SDK 执行，同时保留源 WORKBOOK 电子表格的主要结构和逻辑内容。我们的 Java 库是在线将 WORKBOOK 对象导出为 DOCX 格式文件的专业解决方案。该Cloud SDK为Java开发者提供了强大的功能和完美的DOCX输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java 中的代码示例使用 REST API 将电子表格中的 WORKBOOK 导出为 DOCX 格式" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.*;
    import java.util.HashMap;
    import java.util.List;
    import java.util.Base64;
    import com.aspose.cloud.cells.api.*;
    import com.aspose.cloud.cells.model.*;
    public class Export {
        public static void main(String[] args) {
            String format = "docx";
            String objectType = "workbook";
            HashMap<String,File> fileMap = new HashMap<String,File>();
            fileMap.put("Book1.xlsx" ,new File("C:\Book1.xlsx") );
            fileMap.put("myDocument.xlsx" ,new File("C:\myDocument.xlsx") );
            try {
                LightCellsApi cellsApi = new LightCellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"),"v3.0","https://api.aspose.cloud");
                FilesResult response = cellsApi.postExport(fileMap,objectType, format,null);            
                List<FileInfo> files = response.getFiles();
                String filename = files.get(0).getFilename();
                String fileContent = files.get(0).getFileContent();
                byte[] data = Base64.getDecoder().decode(fileContent);
                OutputStream outputStream = new FileOutputStream(filename);
                outputStream.write(data,0,data.length);
                outputStream.close();
            }catch(Exception exception )
            {
                System.out.print(exception);
            }
        }
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用Cells Cloud SDK for Java将对象从Excel WORKBOOK导出到DOCX" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>使用您的客户端 ID、客户端密钥、基本 URL 和 API 版本初始化 Cells API。</li>
<li>使用 `postExport` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Maven 2.2.0 或更高版本</li>
<li>Java(TM) SE 运行时环境</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
