﻿---
title:  Konvertieren Sie XLSB in DIF mit Android
description:  Verwendung des Cloud SDK Aspose.Cells für Android zum Konvertieren einer XLSB-Formatdatei in eine DIF-Formatdatei.
kwords: Excel, Convert XLSB to DIF, REST, Android
howto: How to convert XLSB to DIF using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie XLSB in DIF" h2="Android-Bibliothek zum Konvertieren von XLSB in DIF" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Android-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XLSB in DIF und andere Dokumentformate mit Android." urlsection="conversion/xlsb-to-dif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie XLSB in DIF mit dem Cloud SDK Cells für Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLSB in DIF kann eine komplexe Aufgabe sein. Unser Android SDK übernimmt alle XLSB-in-DIF-Formatkonvertierungen und behält dabei den wichtigsten strukturellen und logischen Inhalt der XLSB-Quelltabelle bei. Unsere Android-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von XLSB- in DIF-Dateien. Dieses Cloud SDK bietet Android-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige DIF-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android-Codebeispiel für die Konvertierung von XLSB in DIF mithilfe des Cloud SDK Cells" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xlsb";
                String format = "dif";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.dif";
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
