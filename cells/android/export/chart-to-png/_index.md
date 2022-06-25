---
title: Export Chart to PNG file via Android
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Export workbok or interanl object to kinds of format file in the Cloud.
url: /android/export/chart-to-png/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Export Chart to PNG file in the Cloud" h2="Excel & OpenOffice spreadsheet export with open source Cloud SDK for Android">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export Chart to PNG file in Cloud SDK for Android " %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```LightCellsAPI``` with Client Id, Client Secret, Base URL & API version
1. Call ```postExport``` method to get the resultant PNG stream
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for .NET source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) to compile the SDK yourself or head to the [Releases](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/releases) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/#/LightCells/PostExport) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android Code for CHART to PNG Conversion" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
import java.io.*;
import java.util.HashMap;
import java.util.List;
import java.util.Base64;
import com.aspose.cloud.cells.api.*;
import com.aspose.cloud.cells.model.*;
public class Export {
    public static void main(String[] args) {
        String format = "png";
        String objectType = "chart";
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

{{% /blocks/products/pf/agp/code-autogen %}}
{{% blocks/products/cells/cells-cloud-api-run-export  InputFormat="xlsx,*.xls,*.csv,*.txt,*.ods"  OutputFormat=png  ExportObjectType=chart %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
