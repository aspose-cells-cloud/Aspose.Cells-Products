---
title: Convert NUMBERS to MD using Android 
description: Utilizing the Aspose.Cells Cloud SDK for Android to convert a NUMBERS format file to a MD format file. 
kwords: Excel, Convert NUMBERS to MD, REST, Android
howto: How to convert NUMBERS to MD using Aspose.Cells Cloud Android library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert NUMBERS to MD" h2="Android library for converting NUMBERS to MD" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Android projects. This is a professional solution to convert NUMBERS to MD and other document formats online using Android." urlsection="conversion/numbers-to-md/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert NUMBERS to MD using Cells Cloud SDK for Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from NUMBERS to MD can be a complex task. Our Android SDK handles all NUMBERS to MD format conversions while preserving the main structural and logical content of the source NUMBERS spreadsheet. Our Android library provides a professional solution for converting NUMBERS to MD files online. This Cloud SDK empowers Android developers with powerful functionality and ensures high-quality MD output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android Code Example for converting NUMBERS to MD using Cells Cloud SDK" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.numbers";
                String format = "md";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.md";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Android to convert Excel files to other formats" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Use the `putConvertWorkbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Android 7 or newer</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
