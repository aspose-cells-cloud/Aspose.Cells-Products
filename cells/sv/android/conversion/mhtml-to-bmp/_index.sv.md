---
title:  Konvertera MHTML till BMP med Android
description:  Använda Aspose.Cells Cloud SDK för Android för att konvertera en fil i MHTML-format till en fil i BMP-format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertera MHTML till BMP" h2="Android-bibliotek för att konvertera MHTML till BMP" p="Använd Conversion API of of Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Android-projekt. Detta är en professionell lösning för att konvertera MHTML till BMP och andra dokumentformat online med Android." urlsection="conversion/mhtml-to-bmp/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera MHTML till BMP med Cells Cloud SDK för Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från MHTML till BMP kan vara en komplex uppgift. Vår Android SDK hanterar alla MHTML till BMP formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i källarket för MHTML bevaras. Vårt Android-bibliotek erbjuder en professionell lösning för att konvertera MHTML till BMP-filer online. Denna Cloud SDK ger Android-utvecklare kraftfull funktionalitet och säkerställer högkvalitativa BMP-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Android-kodexempel för att konvertera MHTML till BMP med Cells Cloud SDK" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.mhtml";
                String format = "bmp";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.bmp";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för Android för att konvertera Excel-filer till andra format MHTML till BMP" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `putConvertWorkbook` för att hämta den resulterande strömmen.</li>
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
