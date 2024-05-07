---
title: 使用 Java 将 XLS 转换为 MHTML
description: 利用Aspose.Cells Cloud SDK for Java将XLS格式文件转换为MHTML格式文件。
kwords: Excel, Convert XLS to MHTML, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLS to MHTML using the Cells Cloud Java library.","description": "How to convert XLS to MHTML using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/conversion/xls-to-mhtml/","step": [{ "@type": "HowToStep","name": "How to convert XLS to MHTML using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/xls-to-mhtml/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLS to MHTML using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/xls-to-mhtml/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLS to MHTML using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/xls-to-mhtml/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to convert XLS to MHTML using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/xls-to-mhtml/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="将 XLS 转换为 MHTML" h2="Java 用于将 XLS 转换为 MHTML 的库" p="使用 Cells Cloud 的转换 API 在 Java 项目中创建自定义电子表格工作流。这是使用 Java 在线将 XLS 转换为 MHTML 和其他文档格式的专业解决方案。" urlsection="conversion/xls-to-mhtml/" >}}

{{< blocks/products/cells/cells-cloud-section title="使用 Cells Cloud SDK for Java 将 XLS 转换为 MHTML" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
将文件格式从 XLS 转换为 MHTML 可能是一项复杂的任务。我们的 Java SDK 可处理所有 XLS 到 MHTML 格式的转换，同时保留源 XLS 电子表格的主要结构和逻辑内容。我们的 Java 库提供了将 XLS 文件在线转换为 MHTML 文件的专业解决方案。此 Cloud SDK 为 Java 开发人员提供了强大的功能，并确保了高质量的 MHTML 输出。

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java 使用 Cells Cloud SDK 将 XLS 转换为 MHTML 的代码示例" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xls";
            String format = "mhtml";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.mhtml";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="如何使用 Cells 云 Java 库将 XLS 转换为 MHTML。" >}}
<li>注册一个帐户<a href="https://dashboard.aspose.cloud/">仪表板</a>获取免费API配额和授权详细信息</li>
<li>安装 Java 库并将引用（导入库）添加到您的项目中。</li>
<li>打开Java中的源文件。</li>
<li>使用 `putConvertWorkbook` 方法检索结果流。</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="系统要求" >}}
<li>Maven 2.2.0 或更高版本</li>
<li>Java(TM) SE 运行时环境</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
