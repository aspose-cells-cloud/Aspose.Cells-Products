---
title:  Spara HTML som FODS med Java
description:  Använder Aspose.Cells Cloud SDK for Java för att spara HTML filformat som FODS format fil.
kwords: Excel, Save HTML as FODS, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save HTML as FODS using the Cells Cloud Java library.","description": "How to save HTML as FODS using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/saveas/html-to-fods/","step": [{ "@type": "HowToStep","name": "How to save HTML as FODS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/html-to-fods/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save HTML as FODS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/html-to-fods/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save HTML as FODS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/html-to-fods/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to save HTML as FODS using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/html-to-fods/","text": "Use the `postWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Spara HTML som FODS" h2="Java bibliotek för att spara HTML som FODS" p="Använd SaveAs API av Cells Cloud för att skapa anpassade arbetsflöden för kalkylblad i Java. Detta är en professionell lösning för att spara HTML som FODS och andra dokumentformat online med Java." urlsection="saveas/html-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Spara en HTML-fil som FODS i Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från HTML som FODS är en komplex uppgift. Alla formatövergångar från HTML till FODS utförs av vår Java SDK samtidigt som källbladets HTML kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Java-bibliotek är en professionell lösning för att spara HTML som FODS-filer online. Denna Cloud SDK ger Java utvecklare kraftfull funktionalitet och perfekt FODS-utgång.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Kod Exempel för att spara HTML som FODS med REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.html";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.fods";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man sparar HTML som FODS med hjälp av Cells Cloud Java-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Java-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Java.</li>
<li>Använd metoden `postWorkbookSaveAs` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Maven 2.2.0 eller nyare</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
