---
title: Convert JSON to XLT via Android
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Create, Edit, Render or Convert spreadsheet in the Cloud.
url: /android/conversion/json-to-xlt/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert JSON to  XLT in the Cloud" h2="Excel & OpenOffice spreadsheet conversion with open source Cloud SDK for Android">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="JSON to XLT Conversion in Cloud SDK for Android " %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApi``` with Client Id, Client Secret, Base URL & API version
1. Call ```cellsWorkbookPutConvertWorkbook``` method to get the resultant XLT stream
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for .NET source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) to compile the SDK yourself or head to the [Releases](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/releases) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android Code for JSON to XLT Conversion" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.json";
            String format = "xlt";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xlt";
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

{{% /blocks/products/pf/agp/code-autogen %}}
{{% blocks/products/cells/cells-cloud-api-run-conversion  inputformat=json  outputformat=xlt  %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
