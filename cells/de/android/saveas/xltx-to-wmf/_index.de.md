﻿---
title:  XLTX als WMF mit Android speichern
description:  Verwenden Sie das Aspose.Cells Cloud SDK für Android, um Dateien im XLTX-Format als Dateien im WMF-Format zu speichern.
kwords: Excel, Save XLTX as WMF, REST, Android
howto: How to save XLTX as WMF using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="XLTX als WMF speichern" h2="Android-Bibliothek zum Speichern von XLTX als WMF" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Android zu erstellen. Dies ist eine professionelle Lösung zum Online-Speichern von XLTX als WMF und anderen Dokumentformaten mit Android." urlsection="saveas/xltx-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine XLTX-Datei als WMF in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten von XLTX als WMF ist eine komplexe Aufgabe. Alle XLTX-zu-WMF-Formatübergänge werden von unserem Android SDK durchgeführt, während die wichtigsten strukturellen und logischen Inhalte der XLTX-Quelltabelle erhalten bleiben. Unsere Android-Bibliothek ist eine professionelle Lösung, um XLTX als WMF-Dateien online zu speichern. Dieses Cloud SDK bietet Android-Entwicklern leistungsstarke Funktionalität und perfekte WMF-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android-Codebeispiel zum Speichern von XLTX als WMF mit REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xltx";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.wmf";
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
