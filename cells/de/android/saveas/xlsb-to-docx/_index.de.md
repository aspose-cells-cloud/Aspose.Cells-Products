﻿---
title:  Speichern Sie XLSB als DOCX API für Android
description:  Cloud-APIs und SDKs für Microsoft Excel und OpenOffice Calc. Konvertieren Sie die Tabelle in ein anderes Dateiformat.
url: /de/android/saveas/xlsb-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API zum Speichern von XLSB als DOCX" h2="Android-Bibliothek zum Speichern von XLSB als DOCX" p="Verwenden Sie Cells SaveAs REST API, um benutzerdefinierte Tabellenkalkulations-Workflows in Android zu erstellen. Dies ist eine professionelle Lösung, um XLSB als DOCX und andere Dokumentformate online mit Android zu speichern." urlsection="saveas/xlsb-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Speichern Sie eine XLSB-Datei als DOCX in Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus XLSB als DOCX ist eine komplexe Aufgabe. Alle XLSB-zu-DOCX-Formatübergänge werden von unserem Android SDK durchgeführt, während der strukturelle und logische Hauptinhalt der XLSB-Quelltabelle beibehalten wird. Unsere Android-Bibliothek ist eine professionelle Lösung, um XLSB als DOCX-Dateien online zu speichern. Dieses Cloud SDK bietet Android-Entwicklern leistungsstarke Funktionen und eine perfekte DOCX-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Codebeispiel in Android mit REST API zum Speichern von XLSB im DOCX-Format" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.xlsb";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.docx";
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
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Java API, um XLSB als DOCX zu speichern" >}}
<li> Erstellen Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um kostenlose API Kontingent- und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie CellsApi mit Client-ID, Client-Geheimnis, Basis-URL und API-Version</li>
<li>Rufen Sie die Methode cellsSaveAsPostDocumentSaveAs auf, um den resultierenden Stream abzurufen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Android 7 oder neuer</li>
<li>Java(TM) SE Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}