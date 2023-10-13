﻿---
title:  CSV till MD Konvertera API for Java
description: Använder Aspose.Cells Cloud SDK for Java för att konvertera CSV-fil till MD-fil.
url: /sv/java/conversion/csv-to-md/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API för att konvertera CSV till MD" h2="Java bibliotek för att konvertera CSV till MD" p="Använd Cells Conversion REST API för att skapa anpassade arbetsflöden för kalkylblad i Java. Detta är en professionell lösning för att konvertera CSV till MD och andra dokumentformat online med Java." urlsection="conversion/csv-to-md/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera en CSV-fil till MD i Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från CSV till MD är en komplex uppgift. Alla CSV- till MD-formatövergångar utförs av vår Java SDK samtidigt som käll-CSV-kalkylarkets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Java-bibliotek är en professionell lösning för att konvertera CSV- till MD-filer online. Denna Cloud SDK ger Java utvecklare kraftfull funktionalitet och perfekt MD-utgång.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Java med REST API för att konvertera CSV till MD-format" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.csv";
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
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Java API för att konvertera CSV till MD" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop cellsWorkbookPutConvertWorkbook-metoden för att få den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Maven 2.2.0 eller nyare</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}