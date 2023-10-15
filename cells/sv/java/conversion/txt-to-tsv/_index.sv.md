---
title:  Konvertera TXT till TSV med Java
description:  Använda Aspose.Cells Cloud SDK for Java för att konvertera en fil i TXT-format till en fil i TSV-format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertera TXT till TSV" h2="Java bibliotek för att konvertera TXT till TSV" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Java projekt. Detta är en professionell lösning för att konvertera TXT till TSV och andra dokumentformat online med Java." urlsection="conversion/txt-to-tsv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera TXT till TSV med Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från TXT till TSV kan vara en komplex uppgift. Vår Java SDK hanterar alla konverteringar av TXT till TSV-format samtidigt som det huvudsakliga strukturella och logiska innehållet i källarket för TXT bevaras. Vårt Java-bibliotek tillhandahåller en professionell lösning för att konvertera TXT till TSV-filer online. Denna Cloud SDK ger Java utvecklare kraftfull funktionalitet och säkerställer högkvalitativa TSV-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Kodexempel för att konvertera TXT till TSV med Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.txt";
            String format = "tsv";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.tsv";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK for Java för att konvertera Excel filer till andra format TXT till TSV" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `putConvertWorkbook` för att hämta den resulterande strömmen.</li>
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
