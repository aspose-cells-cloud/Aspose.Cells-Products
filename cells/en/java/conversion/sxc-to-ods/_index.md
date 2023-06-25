---
title: SXC to ODS Convert API for Java 
description: Using Aspose.Cells Cloud SDK for Java to convert SXC format file to ODS format file. 
url: /java/conversion/sxc-to-ods/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API to convert SXC to ODS" h2="Java library to convert SXC to ODS" p="Use Cells Conversion REST API to create customized spreadsheet workflows in Java. This is a professional solution to convert SXC to ODS and other document formats online using Java." urlsection="conversion/sxc-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert a SXC file to ODS in Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from SXC to ODS is a complex task. All SXC to ODS format transitions is performed by our Java SDK while maintaining the source SXC spreadsheet's main structural and logical content. Our Java library is a professional solution to convert SXC to ODS files online. This Cloud SDK gives Java developers powerful functionality and perfect ODS output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Java using REST API to convert SXC to ODS format" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.sxc";
            String format = "ods";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.ods";
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
 
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Java API to convert  SXC to ODS" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cellsWorkbookPutConvertWorkbook method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Maven 2.2.0 or newer</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
