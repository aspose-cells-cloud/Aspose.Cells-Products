---
title:  Spara XLS som TXT med C#
description:  Använder Aspose.Cells Cloud SDK för C# för att spara XLS-formatfil som TXT-formatfil.
kwords: Excel, Save XLS as TXT, REST, C#
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLS as TXT using the Cells Cloud Net library.","description": "How to save XLS as TXT using the Cells Cloud Net library.","image": {"@type": "ImageObject"},"url": "/net/saveas/xls-to-txt/","step": [{ "@type": "HowToStep","name": "How to save XLS as TXT using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/xls-to-txt/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLS as TXT using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/xls-to-txt/","text": "Install C# library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLS as TXT using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/xls-to-txt/","text": "Open the source file in C#",},{ "@type": "HowToStep","name": "How to save XLS as TXT using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/saveas/xls-to-txt/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Spara XLS som TXT" h2="C# bibliotek för att spara XLS som TXT" p="Använd SaveAs API av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Net. Detta är en professionell lösning för att spara XLS som TXT och andra dokumentformat online med C#." urlsection="saveas/xls-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Spara en XLS-fil som TXT i C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från XLS som TXT är en komplex uppgift. Alla XLS- till TXT-formatövergångar utförs av vår C# SDK samtidigt som käll XLS-kalkylarkets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt C#-bibliotek är en professionell lösning för att spara XLS som TXT-filer online. Denna Cloud SDK ger C# utvecklare kraftfull funktionalitet och perfekt TXT-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Kod Exempel för att spara XLS som TXT med REST API" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xls";
    string newfilename = "Book1SaveAs.txt";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man sparar XLS som TXT med hjälp av Cells Cloud Net-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera C#-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i C#</li>
<li>Använd metoden `PostWorkbookSaveAs` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>NET Framework 4.5.2 eller senare</li>
<li>Net Standard 2.0 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
