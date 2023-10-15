---
title:  Konvertieren Sie XLT mit Android in MHTML
description:  Verwendung des Aspose.Cells Cloud SDK für Android zum Konvertieren einer Datei im XLT-Format in eine Datei im MHTML-Format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertieren Sie XLT in MHTML" h2="Android-Bibliothek zum Konvertieren von XLT in MHTML" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Android-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XLT in MHTML und andere Dokumentformate mit Android." urlsection="conversion/xlt-to-mhtml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie XLT in MHTML mit dem Cloud SDK Cells für Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLT in MHTML kann eine komplexe Aufgabe sein. Unser Android SDK übernimmt alle XLT-in-MHTML-Formatkonvertierungen und behält dabei den wichtigsten strukturellen und logischen Inhalt der XLT-Quelltabelle bei. Unsere Android-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von XLT- in MHTML-Dateien. Dieses Cloud SDK bietet Android-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige MHTML-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Android-Codebeispiel für die Konvertierung von XLT in MHTML mit dem Cloud SDK Cells" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xlt";
                String format = "mhtml";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.mhtml";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie das Cells Cloud SDK für Android, um Excel-Dateien in andere Formate, XLT in MHTML, zu konvertieren" >}}
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
