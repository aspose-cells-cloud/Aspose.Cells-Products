﻿---
title:  Speichern Sie TSV als TXT mit Android
description:  Verwendung von Aspose.Cells Cloud SDK für Android zum Speichern von TSV-Formatdateien als TXT-Formatdateien.
kwords: Excel, Save TSV as TXT, REST, Android
howto: How to save TSV as TXT using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="TSV als TXT speichern" h2="Android-Bibliothek zum Speichern von TSV als TXT" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Android zu erstellen. Dies ist eine professionelle Lösung, um TSV als TXT und andere Dokumentformate online mit Android zu speichern." urlsection="saveas/tsv-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine TSV-Datei als TXT in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten von TSV als TXT ist eine komplexe Aufgabe. Alle Formatübergänge von TSV zu TXT werden von unserem Android SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quelltabelle TSV erhalten bleibt. Unsere Android-Bibliothek ist eine professionelle Lösung zum Online-Speichern von TSV als TXT-Dateien. Dieses Cloud SDK bietet Android-Entwicklern leistungsstarke Funktionen und eine perfekte TXT-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android-Codebeispiel zum Speichern von TSV als TXT mit REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.tsv";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.txt";
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
