---
title:  Speichern Sie FODS als MHTML mit Java
description: Verwendung von Aspose.Cells Cloud SDK for Java zum Speichern der FODS-Formatdatei als MHTML-Formatdatei.
kwords: Excel, Save FODS as MHTML, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save FODS as MHTML using the Cells Cloud Java library.","description": "How to save FODS as MHTML using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/saveas/fods-to-mhtml/","step": [{ "@type": "HowToStep","name": "How to save FODS as MHTML using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/fods-to-mhtml/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save FODS as MHTML using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/fods-to-mhtml/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save FODS as MHTML using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/fods-to-mhtml/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to save FODS as MHTML using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/fods-to-mhtml/","text": "Use the `postWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie FODS als MHTML" h2="Java Bibliothek zum Speichern von FODS als MHTML" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Java zu erstellen. Dies ist eine professionelle Lösung, um FODS als MHTML und andere Dokumentformate online mit Java zu speichern." urlsection="saveas/fods-to-mhtml/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine FODS-Datei als MHTML unter Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus FODS als MHTML ist eine komplexe Aufgabe. Alle FODS-zu-MHTML-Formatübergänge werden von unserem SDK Java durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quell-FODS-Tabelle erhalten bleibt. Unsere Java-Bibliothek ist eine professionelle Lösung, um FODS als MHTML-Dateien online zu speichern. Dieses Cloud SDK bietet Java Entwicklern leistungsstarke Funktionalität und perfekte MHTML-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Codebeispiel zum Speichern von FODS als MHTML mit REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.fods";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.mhtml";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So speichern Sie FODS als MHTML mit der Cells Cloud Java-Bibliothek." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek Java und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Java.</li>
<li>Verwenden Sie die Methode `postWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Maven 2.2.0 oder neuer</li>
<li>Java(TM) SE-Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
