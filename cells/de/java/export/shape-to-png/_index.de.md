---
title:  Exportieren Sie SHAPE von Excel nach PNG mit Cells Cloud SDK for Java
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
kwords: Excel, shape, png, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to PNG","description": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to PNG","image": {"@type": "ImageObject"},"url": "/java/export/shape-to-png/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to PNG step 1", "image": {"@type": "ImageObject",},"url": "/java/export/shape-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to PNG step 1", "image": {"@type": "ImageObject",},"url": "/java/export/shape-to-png/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel SHAPE to PNG step 1", "image": {"@type": "ImageObject",},"url": "/java/export/shape-to-png/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportieren Sie SHAPE von Excel nach PNG" h2="Java-Bibliothek zum Exportieren von SHAPE in die PNG-Datei" p="Verwenden Sie Export API aus Cells Cloud, um interne Objekt-Workflows aus Excel-Dateien in Java zu exportieren. Dies ist eine professionelle Lösung, um SHAPE mithilfe von Java online aus einer Tabellenkalkulation in eine Datei im PNG-Format zu exportieren." urlsection="export/shape-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportieren Sie das SHAPE-Objekt in eine Datei im Format PNG mit dem Cloud SDK Cells for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren von SHAPE-Objekten in eine PNG-Datei aus einer Excel-Datei ist eine komplexe Aufgabe. Der Export von SHAPE in eine PNG-Formatübergänge wird von unserem Java-SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quell-SHAPE-Tabelle erhalten bleibt. Unsere Java-Bibliothek ist eine professionelle Lösung, um SHAPE-Objekte online in PNG-Formatdateien zu exportieren. Dieses Cloud-SDK bietet Java-Entwicklern leistungsstarke Funktionen und perfekte PNG-Ausgaben.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Codebeispiel in Java unter Verwendung von REST API zum Exportieren von SHAPE aus einer Tabelle in das Format PNG" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.*;
    import java.util.HashMap;
    import java.util.List;
    import java.util.Base64;
    import com.aspose.cloud.cells.api.*;
    import com.aspose.cloud.cells.model.*;
    public class Export {
        public static void main(String[] args) {
            String format = "png";
            String objectType = "shape";
            HashMap<String,File> fileMap = new HashMap<String,File>();
            fileMap.put("Book1.xlsx" ,new File("C:\Book1.xlsx") );
            fileMap.put("myDocument.xlsx" ,new File("C:\myDocument.xlsx") );
            try {
                LightCellsApi cellsApi = new LightCellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"),"v3.0","https://api.aspose.cloud");
                FilesResult response = cellsApi.postExport(fileMap,objectType, format,null);            
                List<FileInfo> files = response.getFiles();
                String filename = files.get(0).getFilename();
                String fileContent = files.get(0).getFileContent();
                byte[] data = Base64.getDecoder().decode(fileContent);
                OutputStream outputStream = new FileOutputStream(filename);
                outputStream.write(data,0,data.length);
                outputStream.close();
            }catch(Exception exception )
            {
                System.out.print(exception);
            }
        }
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK for Java, um Objekte von Excel SHAPE nach PNG zu exportieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `postExport`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Maven 2.2.0 oder neuer</li>
<li>Java(TM) SE-Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
