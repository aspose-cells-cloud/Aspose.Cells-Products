﻿---
title:  Speichern Sie XLT als XLSB mit Android
description:  Verwendung des Cloud SDK Aspose.Cells für Android zum Speichern von XLT-Formatdateien als XLSB-Formatdateien.
kwords: Excel, Save XLT as XLSB, REST, Android
howto: How to save XLT as XLSB using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie XLT als XLSB" h2="Android-Bibliothek zum Speichern von XLT als XLSB" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Android zu erstellen. Dies ist eine professionelle Lösung, um XLT als XLSB und andere Dokumentformate online mit Android zu speichern." urlsection="saveas/xlt-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine XLT-Datei als XLSB in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten von XLT als XLSB ist eine komplexe Aufgabe. Alle Formatübergänge von XLT nach XLSB werden von unserem Android SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quell-XLT-Tabelle erhalten bleibt. Unsere Android-Bibliothek ist eine professionelle Lösung zum Online-Speichern von XLT als XLSB-Dateien. Dieses Cloud SDK bietet Android-Entwicklern leistungsstarke Funktionen und eine perfekte XLSB-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android-Codebeispiel zum Speichern von XLT als XLSB mit REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xlt";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xlsb";
    String folder ="CellsTests";
    try
    {
        CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
        cellsApi.cellsSaveAsPostDocumentSaveAs(name , saveOptions,newfilename,false,false,folder,null,null,null,true);                       
    }
    catch(Exception exception )
    {
        System.out.print(exception);
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie das Cells Cloud SDK für Android, um Excel-Dateien in anderen Formaten zu speichern" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `postWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Android 7 oder neuer</li>
<li>Java(TM) SE-Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
