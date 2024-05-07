---
title:  Konvertieren Sie PNG mit Java in JPG
description:  Verwendung des Aspose.Cells Cloud SDK for Java zum Konvertieren einer Datei im Format PNG in eine Datei im JPG-Format.
kwords: Excel, Convert PNG to JPG, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert PNG to JPG using the Cells Cloud Java library.","description": "How to convert PNG to JPG using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/conversion/png-to-jpg/","step": [{ "@type": "HowToStep","name": "How to convert PNG to JPG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/png-to-jpg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert PNG to JPG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/png-to-jpg/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert PNG to JPG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/png-to-jpg/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to convert PNG to JPG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/png-to-jpg/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie PNG in JPG" h2="Java-Bibliothek zum Konvertieren von PNG in JPG" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Java-Projekten zu erstellen. Dies ist eine professionelle Lösung, um PNG online mit Java in JPG und andere Dokumentformate zu konvertieren." urlsection="conversion/png-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie PNG mit Cells Cloud SDK for Java in JPG" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von PNG in JPG kann eine komplexe Aufgabe sein. Unser Java SDK übernimmt alle Konvertierungen von PNG in das JPG-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der Quelltabelle PNG bei. Unsere Java-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von PNG in JPG-Dateien. Dieses Cloud SDK bietet Java-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige JPG-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Codebeispiel für die Konvertierung von PNG in JPG mit Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.png";
            String format = "jpg";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.jpg";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So konvertieren Sie PNG mithilfe der Cells Cloud Java-Bibliothek in JPG." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek Java und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Java.</li>
<li>Verwenden Sie die Methode `putConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Maven 2.2.0 oder neuer</li>
<li>Java(TM) SE-Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
