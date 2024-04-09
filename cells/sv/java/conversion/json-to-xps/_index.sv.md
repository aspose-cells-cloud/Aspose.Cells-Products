---
title:  Konvertera JSON till XPS med Java
description: Använda Aspose.Cells Cloud SDK for Java för att konvertera en fil i JSON-format till en fil i XPS-format.
kwords: Excel, Convert JSON to XPS, REST, Java
howto: How to convert JSON to XPS using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera JSON till XPS" h2="Java bibliotek för att konvertera JSON till XPS" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Java projekt. Detta är en professionell lösning för att konvertera JSON till XPS och andra dokumentformat online med Java." urlsection="conversion/json-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera JSON till XPS med Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från JSON till XPS kan vara en komplex uppgift. Vår Java SDK hanterar alla JSON- till XPS-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i käll-JSON-kalkylarket bevaras. Vårt Java-bibliotek tillhandahåller en professionell lösning för att konvertera JSON-filer till XPS-filer online. Denna Cloud SDK ger Java-utvecklare kraftfull funktionalitet och säkerställer högkvalitativa XPS-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Kodexempel för att konvertera JSON till XPS med Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.json";
            String format = "xps";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xps";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Lär dig hur du konverterar JSON till XPS med hjälp av Cells Cloud Java-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Java-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Java.</li>
<li>Använd metoden `putConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Maven 2.2.0 eller nyare</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
