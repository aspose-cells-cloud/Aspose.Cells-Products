---
title:  Konvertieren Sie NUMBERS mit Android in XLTM
description:  Verwendung des Aspose.Cells Cloud SDK für Android zum Konvertieren einer Datei im NUMBERS-Format in eine Datei im XLTM-Format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertieren Sie NUMBERS in XLTM" h2="Android-Bibliothek zum Konvertieren von NUMBERS in XLTM" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Android-Projekten zu erstellen. Dies ist eine professionelle Lösung, um NUMBERS online mit Android in XLTM und andere Dokumentformate zu konvertieren." urlsection="conversion/numbers-to-xltm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie NUMBERS mit dem Cloud SDK Cells für Android in XLTM" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von NUMBERS in XLTM kann eine komplexe Aufgabe sein. Unser Android SDK übernimmt alle Konvertierungen von NUMBERS in das XLTM-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der NUMBERS-Quelltabelle bei. Unsere Android-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von NUMBERS in XLTM-Dateien. Dieses Cloud SDK bietet Android-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige XLTM-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Android-Codebeispiel für die Konvertierung von NUMBERS in XLTM mithilfe des Cloud SDK Cells" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.numbers";
                String format = "xltm";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.xltm";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie das Cells Cloud SDK für Android, um Excel-Dateien in andere Formate von NUMBERS in XLTM zu konvertieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `putConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Android 7 oder neuer</li>
<li>Java(TM) SE-Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
