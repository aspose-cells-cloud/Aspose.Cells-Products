﻿---
title:  JPG till FODS Konvertera API för Android
description:  Använder Aspose.Cells Cloud SDK för Android för att konvertera fil i JPG-format till fil i FODS-format.
url: /sv/android/conversion/jpg-to-fods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API för att konvertera JPG till FODS" h2="Android-bibliotek för att konvertera JPG till FODS" p="Använd Cells Conversion REST API för att skapa anpassade arbetsflöden för kalkylblad i Android. Detta är en professionell lösning för att konvertera JPG till FODS och andra dokumentformat online med Android." urlsection="conversion/jpg-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera en JPG-fil till FODS i Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från JPG till FODS är en komplex uppgift. Alla JPG- till FODS-formatövergångar utförs av vår Android SDK samtidigt som käll-JPG-kalkylarkets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Android-bibliotek är en professionell lösning för att konvertera JPG till FODS-filer online. Denna Cloud SDK ger Android-utvecklare kraftfull funktionalitet och perfekt FODS-utgång.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Android med REST API för att konvertera JPG till FODS-format" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.jpg";
                String format = "fods";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.fods";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Java API för att konvertera JPG till FODS" >}}
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