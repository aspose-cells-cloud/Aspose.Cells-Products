---
title: Convert HTML to TXT using Java 
description: Utilizing the Aspose.Cells Cloud SDK for Java to convert a HTML format file to a TXT format file. 
kwords: Excel, Convert HTML to TXT, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert HTML to TXT using the Cells Cloud Java library.","description": "How to convert HTML to TXT using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/conversion/html-to-txt/","step": [{ "@type": "HowToStep","name": "How to convert HTML to TXT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/html-to-txt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert HTML to TXT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/html-to-txt/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert HTML to TXT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/html-to-txt/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to convert HTML to TXT using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/html-to-txt/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert HTML to TXT" h2="Java library for converting HTML to TXT" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Java projects. This is a professional solution to convert HTML to TXT and other document formats online using Java." urlsection="conversion/html-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert HTML to TXT using Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from HTML to TXT can be a complex task. Our Java SDK handles all HTML to TXT format conversions while preserving the main structural and logical content of the source HTML spreadsheet. Our Java library provides a professional solution for converting HTML to TXT files online. This Cloud SDK empowers Java developers with powerful functionality and ensures high-quality TXT output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Code Example for converting HTML to TXT using Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.html";
            String format = "txt";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.txt";
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
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to convert HTML to TXT using the Cells Cloud Java library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Java library and add the reference (import the library) to your project.</li>
<li>Open the source file in Java.</li>
<li>Use the `putConvertWorkbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Maven 2.2.0 or newer</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
