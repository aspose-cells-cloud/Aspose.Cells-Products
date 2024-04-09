---
title:  Konvertera XLSB till DOCX med Java
description:  Använda Aspose.Cells Cloud SDK for Java för att konvertera en fil i XLSB-format till en fil i DOCX-format.
kwords: Excel, Convert XLSB to DOCX, REST, Java
howto: How to convert XLSB to DOCX using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera XLSB till DOCX" h2="Java bibliotek för att konvertera XLSB till DOCX" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Java projekt. Detta är en professionell lösning för att konvertera XLSB till DOCX och andra dokumentformat online med Java." urlsection="conversion/xlsb-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera XLSB till DOCX med Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLSB till DOCX kan vara en komplex uppgift. Vår Java SDK hanterar alla XLSB- till DOCX-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i källbladets XLSB-kalkylblad bevaras. Vårt Java-bibliotek tillhandahåller en professionell lösning för att konvertera XLSB till DOCX-filer online. Denna Cloud SDK ger Java utvecklare kraftfull funktionalitet och säkerställer DOCX-utdata av hög kvalitet.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Kodexempel för att konvertera XLSB till DOCX med Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xlsb";
            String format = "docx";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.docx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Lär dig hur du konverterar XLSB till DOCX med hjälp av Cells Cloud Java-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Java-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Java.</li>
<li>Använd metoden `putConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Maven 2.2.0 eller nyare</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
