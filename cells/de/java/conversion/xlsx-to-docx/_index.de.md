﻿---
title:  XLSX-zu-DOCX-Konvertierung API for Java
description:  Cloud-APIs und SDKs für Microsoft Excel und OpenOffice Calc. Konvertieren Sie die Tabelle in ein anderes Dateiformat.
url: /de/java/conversion/xlsx-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API um XLSX in DOCX umzuwandeln" h2="Java-Bibliothek zum Konvertieren von XLSX in DOCX" p="Verwenden Sie Cells Conversion REST API, um benutzerdefinierte Tabellenkalkulations-Workflows in Java zu erstellen. Dies ist eine professionelle Lösung zur Online-Konvertierung von XLSX in DOCX und andere Dokumentformate mit Java." urlsection="conversion/xlsx-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie eine XLSX-Datei in Java in DOCX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLSX in DOCX ist eine komplexe Aufgabe. Alle XLSX-zu-DOCX-Formatübergänge werden von unserem Java SDK durchgeführt, während der strukturelle und logische Hauptinhalt der XLSX-Quelltabelle beibehalten wird. Unsere Java-Bibliothek ist eine professionelle Lösung, um XLSX-Dateien online in DOCX-Dateien zu konvertieren. Dieses Cloud-SDK bietet Java-Entwicklern leistungsstarke Funktionen und eine perfekte DOCX-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in Java mit REST API zum Konvertieren von XLSX in das DOCX-Format" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xlsx";
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
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Java API, um XLSX in DOCX zu konvertieren" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um kostenlose API Kontingent- und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und API-Version</li>
<li>Rufen Sie die Methode cellWorkbookPutConvertWorkbook auf, um den resultierenden Stream abzurufen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Maven 2.2.0 oder neuer</li>
<li>Java(TM) SE Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}