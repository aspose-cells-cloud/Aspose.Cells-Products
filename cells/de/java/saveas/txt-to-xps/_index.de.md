---
title:  Speichern Sie TXT unter XPS mit Java
description:  Verwendung von Aspose.Cells Cloud SDK for Java zum Speichern der TXT-Formatdatei als XPS-Formatdatei.
kwords: Excel, Save TXT as XPS, REST, Java
howto: How to save TXT as XPS using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie TXT unter XPS" h2="Java-Bibliothek zum Speichern von TXT als XPS" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Java zu erstellen. Dies ist eine professionelle Lösung, um TXT als XPS und andere Dokumentformate online unter Java zu speichern." urlsection="saveas/txt-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine TXT-Datei unter XPS in Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus TXT als XPS ist eine komplexe Aufgabe. Alle TXT-Formatübergänge in das XPS-Format werden von unserem Java-SDK durchgeführt, wobei der strukturelle und logische Hauptinhalt der TXT-Quelltabelle erhalten bleibt. Unsere Java-Bibliothek ist eine professionelle Lösung, um TXT als XPS-Dateien online zu speichern. Dieses Cloud SDK bietet Java Entwicklern leistungsstarke Funktionalität und eine perfekte XPS Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Codebeispiel zum Speichern von TXT als XPS mit REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.txt";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xps";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Erfahren Sie, wie Sie TXT mithilfe der Cells Cloud Java-Bibliothek als XPS speichern." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek Java und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Java.</li>
<li>Verwenden Sie die Methode `postWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Maven 2.2.0 oder neuer</li>
<li>Java(TM) SE-Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
