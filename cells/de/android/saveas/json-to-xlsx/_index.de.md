﻿---
title:  Speichern Sie JSON als XLSX mit Android
description:  Verwendung von Aspose.Cells Cloud SDK für Android zum Speichern von JSON-Formatdateien als XLSX-Formatdateien.
kwords: Excel, Save JSON as XLSX, REST, Android
howto: How to save JSON as XLSX using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie JSON als XLSX" h2="Android-Bibliothek zum Speichern von JSON als XLSX" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Android zu erstellen. Dies ist eine professionelle Lösung zum Online-Speichern von JSON als XLSX und anderen Dokumentformaten mit Android." urlsection="saveas/json-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine JSON-Datei als XLSX in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten von JSON als XLSX ist eine komplexe Aufgabe. Alle Übergänge vom JSON- zum XLSX-Format werden von unserem Android SDK durchgeführt, wobei die wichtigsten strukturellen und logischen Inhalte der Quell-JSON-Tabelle erhalten bleiben. Unsere Android-Bibliothek ist eine professionelle Lösung, um JSON als XLSX-Dateien online zu speichern. Dieses Cloud SDK bietet Android-Entwicklern leistungsstarke Funktionalität und perfekte XLSX-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android-Codebeispiel zum Speichern von JSON als XLSX mit REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.json";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xlsx";
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
