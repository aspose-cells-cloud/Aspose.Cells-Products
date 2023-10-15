---
title:  Konvertieren Sie XLS mit Java in XLTX
description:  Verwendung des Aspose.Cells Cloud SDK for Java zum Konvertieren einer Datei im XLS-Format in eine Datei im XLTX-Format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertieren Sie XLS in XLTX" h2="Java Bibliothek zum Konvertieren von XLS in XLTX" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Java-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XLS in XLTX und andere Dokumentformate unter Java." urlsection="conversion/xls-to-xltx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie XLS in XLTX mit Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLS in XLTX kann eine komplexe Aufgabe sein. Unser Java SDK übernimmt alle XLS-in-XLTX-Formatkonvertierungen und behält dabei den wichtigsten strukturellen und logischen Inhalt der XLS-Quelltabelle bei. Unsere Java-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von XLS- in XLTX-Dateien. Dieses Cloud SDK bietet Java-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige XLTX-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Codebeispiel für die Konvertierung von XLS in XLTX mit Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xls";
            String format = "xltx";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xltx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK for Java zum Konvertieren von Excel-Dateien in andere Formate XLS in XLTX" >}}
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
