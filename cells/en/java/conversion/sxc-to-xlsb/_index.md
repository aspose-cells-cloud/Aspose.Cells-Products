---
title: SXC to XLSB Convert API for Java 
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Convert spreadsheet to other format file. 
url: /java/conversion/sxc-to-xlsb/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API to convert SXC to XLSB" h2="Java library to convert SXC to XLSB" p="Use Cells Conversion REST API to create customized spreadsheet workflows in Java. This is a professional solution to convert SXC to XLSB and other document formats online using Java." urlsection="conversion/sxc-to-xlsb/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert a SXC file to XLSB in Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from SXC to XLSB is a complex task. All SXC to XLSB format transitions is performed by our Java SDK while maintaining the source SXC spreadsheet's main structural and logical content. Our Java library is a professional solution to convert SXC to XLSB files online. This Cloud SDK gives Java developers powerful functionality and perfect XLSB output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Java using REST API to convert SXC to XLSB format" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.sxc";
            String format = "xlsb";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xlsb";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Java API to convert  SXC to XLSB" >}}
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