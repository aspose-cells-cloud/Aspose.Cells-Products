﻿---
title:  Speichern Sie XLT unter Android unter SVG
description:  Verwendung des Aspose.Cells Cloud SDK für Android zum Speichern der XLT-Formatdatei als SVG-Formatdatei.
kwords: Excel, Save XLT as SVG, REST, Android
howto: How to save XLT as SVG using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie XLT unter SVG" h2="Android-Bibliothek zum Speichern von XLT als SVG" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Android zu erstellen. Dies ist eine professionelle Lösung, um XLT als SVG und andere Dokumentformate online mit Android zu speichern." urlsection="saveas/xlt-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine XLT-Datei unter Android als SVG" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus XLT als SVG ist eine komplexe Aufgabe. Alle XLT-Formatübergänge in das SVG-Format werden von unserem Android SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der XLT-Quelltabelle erhalten bleibt. Unsere Android-Bibliothek ist eine professionelle Lösung zum Online-Speichern von XLT-Dateien im Format SVG. Dieses Cloud SDK bietet Android-Entwicklern leistungsstarke Funktionalität und eine perfekte SVG-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android-Codebeispiel zum Speichern von XLT als SVG unter Verwendung von REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xlt";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.svg";
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
