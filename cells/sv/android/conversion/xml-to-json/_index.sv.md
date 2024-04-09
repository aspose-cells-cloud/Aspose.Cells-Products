---
title:  Konvertera XML till JSON med Android
description:  Använda Aspose.Cells Cloud SDK för Android för att konvertera en XML-formatfil till en JSON-formatfil.
kwords: Excel, Convert XML to JSON, REST, Android
howto: How to convert XML to JSON using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera XML till JSON" h2="Android-bibliotek för att konvertera XML till JSON" p="Använd Conversion API of of Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Android-projekt. Detta är en professionell lösning för att konvertera XML till JSON och andra dokumentformat online med Android." urlsection="conversion/xml-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera XML till JSON med Cells Cloud SDK för Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XML till JSON kan vara en komplex uppgift. Vår Android SDK hanterar alla XML- till JSON-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i XML-källarket bevaras. Vårt Android-bibliotek tillhandahåller en professionell lösning för att konvertera XML till JSON-filer online. Denna Cloud SDK ger Android-utvecklare kraftfull funktionalitet och säkerställer JSON-utdata av hög kvalitet.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android-kodexempel för att konvertera XML till JSON med Cells Cloud SDK" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xml";
                String format = "json";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.json";
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
