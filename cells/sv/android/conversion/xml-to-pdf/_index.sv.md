﻿---
title:  XML till PDF Konvertera API för Android
description:  Använda Aspose.Cells Cloud SDK för Android för att konvertera XML-formatfil till PDF-fil.
url: /sv/android/conversion/xml-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API för att konvertera XML till PDF" h2="Android-bibliotek för att konvertera XML till PDF" p="Använd Cells Conversion REST API för att skapa anpassade arbetsflöden för kalkylblad i Android. Detta är en professionell lösning för att konvertera XML till PDF och andra dokumentformat online med Android." urlsection="conversion/xml-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera en XML-fil till PDF i Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XML till PDF är en komplex uppgift. Alla XML- till PDF-formatövergångar utförs av vår Android SDK samtidigt som käll-XML-kalkylarkets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Android-bibliotek är en professionell lösning för att konvertera XML till PDF-filer online. Denna Cloud SDK ger Android-utvecklare kraftfull funktionalitet och perfekt PDF-utgång.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Android med REST API för att konvertera XML till PDF-format" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xml";
                String format = "pdf";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.pdf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Java API för att konvertera XML till PDF" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop cellsWorkbookPutConvertWorkbook-metoden för att få den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Android 7 eller senare</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}