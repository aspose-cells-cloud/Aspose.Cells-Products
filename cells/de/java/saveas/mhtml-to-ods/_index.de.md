---
title:  Speichern Sie MHTML als ODS mit Java
description:  Verwendung von Aspose.Cells Cloud SDK for Java zum Speichern von MHTML-Formatdateien als ODS-Formatdateien.
kwords: Excel, Save MHTML as ODS, REST, Java
howto: How to save MHTML as ODS using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie MHTML als ODS" h2="Java Bibliothek zum Speichern von MHTML als ODS" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Java zu erstellen. Dies ist eine professionelle Lösung, um MHTML als ODS und andere Dokumentformate online mit Java zu speichern." urlsection="saveas/mhtml-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine MHTML-Datei als ODS unter Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus MHTML als ODS ist eine komplexe Aufgabe. Alle MHTML-zu-ODS-Formatübergänge werden von unserem SDK Java durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quell-MHTML-Tabelle erhalten bleibt. Unsere Java-Bibliothek ist eine professionelle Lösung, um MHTML als ODS-Dateien online zu speichern. Dieses Cloud SDK bietet Java Entwicklern leistungsstarke Funktionalität und perfekte ODS-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Codebeispiel zum Speichern von MHTML als ODS mit REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.mhtml";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.ods";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Erfahren Sie, wie Sie MHTML als ODS mit der Cells Cloud Java-Bibliothek speichern." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek Java und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Java.</li>
<li>Verwenden Sie die Methode `postWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Maven 2.2.0 oder neuer</li>
<li>Java(TM) SE-Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
