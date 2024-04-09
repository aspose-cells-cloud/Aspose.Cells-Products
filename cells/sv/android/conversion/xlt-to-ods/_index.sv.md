---
title:  Konvertera XLT till ODS med Android
description:  Använda Aspose.Cells Cloud SDK för Android för att konvertera en fil i XLT-format till en fil i ODS-format.
kwords: Excel, Convert XLT to ODS, REST, Android
howto: How to convert XLT to ODS using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera XLT till ODS" h2="Android-bibliotek för att konvertera XLT till ODS" p="Använd Conversion API of of Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Android-projekt. Detta är en professionell lösning för att konvertera XLT till ODS och andra dokumentformat online med Android." urlsection="conversion/xlt-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera XLT till ODS med Cells Cloud SDK för Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLT till ODS kan vara en komplex uppgift. Vår Android SDK hanterar alla konverteringar av XLT till ODS-format samtidigt som det huvudsakliga strukturella och logiska innehållet i källbladets XLT-kalkylblad bevaras. Vårt Android-bibliotek erbjuder en professionell lösning för att konvertera XLT till ODS-filer online. Denna Cloud SDK ger Android-utvecklare kraftfull funktionalitet och säkerställer ODS-utdata av hög kvalitet.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android-kodexempel för att konvertera XLT till ODS med Cells Cloud SDK" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xlt";
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
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för Android för att konvertera Excel-filer till andra format" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `putConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Android 7 eller senare</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
