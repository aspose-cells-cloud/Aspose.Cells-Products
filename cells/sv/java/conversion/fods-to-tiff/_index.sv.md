---
title: Konvertera FODS till TIFF med Java
description:  Använda Aspose.Cells Cloud SDK for Java för att konvertera en fil i FODS-format till en fil i TIFF-format.
kwords: Excel, Convert FODS to TIFF, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert FODS to TIFF using the Cells Cloud Java library.","description": "How to convert FODS to TIFF using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/conversion/fods-to-tiff/","step": [{ "@type": "HowToStep","name": "How to convert FODS to TIFF using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/fods-to-tiff/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert FODS to TIFF using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/fods-to-tiff/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert FODS to TIFF using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/fods-to-tiff/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to convert FODS to TIFF using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/fods-to-tiff/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera FODS till TIFF" h2="Java bibliotek för att konvertera FODS till TIFF" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Java projekt. Detta är en professionell lösning för att konvertera FODS till TIFF och andra dokumentformat online med Java." urlsection="conversion/fods-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera FODS till TIFF med Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från FODS till TIFF kan vara en komplex uppgift. Vår Java SDK hanterar alla FODS- till TIFF-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i FODS-källbladet bevaras. Vårt Java-bibliotek tillhandahåller en professionell lösning för att konvertera FODS till TIFF-filer online. Denna Cloud SDK ger Java-utvecklare kraftfull funktionalitet och säkerställer högkvalitativa TIFF-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Kod Exempel för att konvertera FODS till TIFF med Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.fods";
            String format = "tiff";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.tiff";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man konverterar FODS till TIFF med hjälp av Cells Cloud Java-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Java-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Java.</li>
<li>Använd metoden `putConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Maven 2.2.0 eller nyare</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
