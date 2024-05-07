---
title:  Speichern Sie HTML als XLS mit Java
description:  Verwendung des Aspose.Cells Cloud SDK for Java zum Speichern der Datei im HTML-Format als XLS-Formatdatei.
kwords: Excel, Save HTML as XLS, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save HTML as XLS using the Cells Cloud Java library.","description": "How to save HTML as XLS using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/saveas/html-to-xls/","step": [{ "@type": "HowToStep","name": "How to save HTML as XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/html-to-xls/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save HTML as XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/html-to-xls/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save HTML as XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/html-to-xls/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to save HTML as XLS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/html-to-xls/","text": "Use the `postWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Speichern Sie HTML als XLS" h2="Java-Bibliothek zum Speichern von HTML als XLS" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Java zu erstellen. Dies ist eine professionelle Lösung, um HTML als XLS und andere Dokumentformate online mit Java zu speichern." urlsection="saveas/html-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine HTML-Datei als XLS in Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten ab HTML als XLS ist eine komplexe Aufgabe. Alle Übergänge vom Format HTML zum XLS-Format werden von unserem SDK Java durchgeführt, wobei der strukturelle und logische Hauptinhalt der Quelltabelle HTML erhalten bleibt. Unsere Java-Bibliothek ist eine professionelle Lösung, um HTML als XLS-Dateien online zu speichern. Dieses Cloud SDK bietet Java Entwicklern leistungsstarke Funktionalität und perfekte XLS-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Codebeispiel zum Speichern von HTML als XLS mit REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.html";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xls";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So speichern Sie HTML als XLS mithilfe der Cells Cloud Java-Bibliothek." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek Java und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Java.</li>
<li>Verwenden Sie die Methode `postWorkbookSaveAs`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Maven 2.2.0 oder neuer</li>
<li>Java(TM) SE-Laufzeitumgebung</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
