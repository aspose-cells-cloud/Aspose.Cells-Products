---
title: NUMBERS to XML Convert API for Android 
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Convert spreadsheet to other format file. 
url: /android/conversion/numbers-to-xml/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API to convert NUMBERS to XML" h2="Android library to convert NUMBERS to XML" p="Use Cells Conversion REST API to create customized spreadsheet workflows in Android. This is a professional solution to convert NUMBERS to XML and other document formats online using Android." urlsection="conversion/numbers-to-xml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert a NUMBERS file to XML in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from NUMBERS to XML is a complex task. All NUMBERS to XML format transitions is performed by our Android SDK while maintaining the source NUMBERS spreadsheet's main structural and logical content. Our Android library is a professional solution to convert NUMBERS to XML files online. This Cloud SDK gives Android developers powerful functionality and perfect XML output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Android using REST API to convert NUMBERS to XML format" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.numbers";
                String format = "xml";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.xml";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Java API to convert  NUMBERS to XML" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cellsWorkbookPutConvertWorkbook method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Android 7 or newer</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}