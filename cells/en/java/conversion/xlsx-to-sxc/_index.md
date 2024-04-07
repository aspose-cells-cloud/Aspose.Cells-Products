---
title: Convert XLSX to SXC using Java 
description: Utilizing the Aspose.Cells Cloud SDK for Java to convert a XLSX format file to a SXC format file. 
kwords: Excel, Convert XLSX to SXC, REST, Java
howto: How to convert XLSX to SXC using Aspose.Cells Cloud Java library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert XLSX to SXC" h2="Java library for converting XLSX to SXC" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Java projects. This is a professional solution to convert XLSX to SXC and other document formats online using Java." urlsection="conversion/xlsx-to-sxc/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert XLSX to SXC using Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XLSX to SXC can be a complex task. Our Java SDK handles all XLSX to SXC format conversions while preserving the main structural and logical content of the source XLSX spreadsheet. Our Java library provides a professional solution for converting XLSX to SXC files online. This Cloud SDK empowers Java developers with powerful functionality and ensures high-quality SXC output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Code Example for converting XLSX to SXC using Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xlsx";
            String format = "sxc";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.sxc";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to convert XLSX to SXC using the Cells Cloud Java library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Java library and add the reference (import the library) to your project.</li>
<li>Open the source file in Java.</li>
<li>Use the `putConvertWorkbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Maven 2.2.0 or newer</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
