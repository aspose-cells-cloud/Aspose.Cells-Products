---
title:  Konvertieren Sie XLTM mit Android in FODS
description: Verwendung des Aspose.Cells Cloud SDK für Android zum Konvertieren einer Datei im XLTM-Format in eine Datei im FODS-Format.
kwords: Excel, Convert XLTM to FODS, REST, Android
howto: How to convert XLTM to FODS using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie XLTM in FODS" h2="Android-Bibliothek zum Konvertieren von XLTM in FODS" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Android-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XLTM in FODS und andere Dokumentformate mit Android." urlsection="conversion/xltm-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie XLTM in FODS mit dem Cloud SDK Cells für Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLTM in FODS kann eine komplexe Aufgabe sein. Unser Android SDK übernimmt alle Konvertierungen von XLTM in das FODS-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der XLTM-Quelltabelle bei. Unsere Android-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von XLTM- in FODS-Dateien. Dieses Cloud SDK bietet Android-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige FODS-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android-Codebeispiel für die Konvertierung von XLTM in FODS mithilfe des Cloud SDK Cells" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xltm";
                String format = "fods";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.fods";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie das Cells Cloud SDK für Android, um Excel-Dateien in andere Formate zu konvertieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `putConvertWorkbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Android 7 oder neuer</li>
<li>Java(TM) SE-Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
