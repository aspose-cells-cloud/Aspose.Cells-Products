﻿---
title:  Speichern Sie NUMBERS als SVG unter Verwendung von Java
description: Verwendung von Aspose.Cells Cloud SDK for Java zum Speichern der Datei im NUMBERS-Format als Datei im Format SVG.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Speichern Sie die Nummern unter SVG" h2="Java-Bibliothek zum Speichern von ZAHLEN als SVG" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Java zu erstellen. Dies ist eine professionelle Lösung, um NUMBERS als SVG und andere Dokumentformate online unter Java zu speichern." urlsection="saveas/numbers-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Speichern Sie eine NUMBERS-Datei unter SVG in Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten von NUMBERS als SVG ist eine komplexe Aufgabe. Alle Formatübergänge von NUMBERS zu SVG werden von unserem Java SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der NUMBERS-Quelltabelle erhalten bleibt. Unsere Java-Bibliothek ist eine professionelle Lösung, um NUMBERS als SVG-Dateien online zu speichern. Dieses Cloud SDK bietet Java Entwicklern leistungsstarke Funktionalität und eine perfekte SVG Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Codebeispiel zum Speichern von ZAHLEN als SVG unter Verwendung von REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.numbers";
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
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK for Java, um Excel-Dateien in anderen Formaten zu speichern. ZAHLEN wie SVG" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `postWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Maven 2.2.0 oder neuer</li>
<li>Java(TM) SE-Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
