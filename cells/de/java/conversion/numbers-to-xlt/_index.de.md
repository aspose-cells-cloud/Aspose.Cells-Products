---
title:  Konvertieren Sie NUMBERS mit Java in XLT
description:  Verwendung des Aspose.Cells Cloud SDK for Java zum Konvertieren einer Datei im NUMBERS-Format in eine Datei im XLT-Format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertieren Sie NUMBERS in XLT" h2="Java Bibliothek zum Konvertieren von NUMBERS in XLT" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Java-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von NUMBERS in XLT und andere Dokumentformate unter Java." urlsection="conversion/numbers-to-xlt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie NUMBERS mit Cells Cloud SDK for Java in XLT" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von NUMBERS in XLT kann eine komplexe Aufgabe sein. Unser SDK Java übernimmt alle Konvertierungen von NUMBERS in das XLT-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der Quelltabelle von NUMBERS bei. Unsere Java-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von NUMBERS in XLT-Dateien. Dieses Cloud SDK bietet Java-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige XLT-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Codebeispiel für die Konvertierung von NUMBERS in XLT mit Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.numbers";
            String format = "xlt";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xlt";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK for Java, um Excel-Dateien in andere Formate von NUMBERS in XLT zu konvertieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `putConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Maven 2.2.0 oder neuer</li>
<li>Java(TM) SE-Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
