---
title:  Spara XML som DIF med Go
description:  Använder Aspose.Cells Cloud SDK för Go för att spara XML-formatfil som DIF-formatfil.
kwords: Excel, Save XML as DIF, REST, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XML as DIF using the Cells Cloud Go library.","description": "How to save XML as DIF using the Cells Cloud Go library.","image": {"@type": "ImageObject"},"url": "/go/saveas/xml-to-dif/","step": [{ "@type": "HowToStep","name": "How to save XML as DIF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/xml-to-dif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XML as DIF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/xml-to-dif/","text": "Install Go library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XML as DIF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/xml-to-dif/","text": "Open the source file in go.",},{ "@type": "HowToStep","name": "How to save XML as DIF using the Cells Cloud Go library. step 1", "image": {"@type": "ImageObject",},"url": "/go/saveas/xml-to-dif/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Spara XML som DIF" h2="Gå bibliotek för att spara XML som DIF" p="Använd SaveAs API av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Go. Detta är en professionell lösning för att spara XML som DIF och andra dokumentformat online med Go." urlsection="saveas/xml-to-dif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Spara en XML-fil som DIF i Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från XML som DIF är en komplex uppgift. Alla XML- till DIF-formatövergångar utförs av vår Go SDK samtidigt som käll-XML-kalkylarkets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Go-bibliotek är en professionell lösning för att spara XML som DIF-filer online. Denna Cloud SDK ger Go-utvecklare kraftfull funktionalitet och perfekt DIF-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Go Code Exempel för att spara XML som DIF med REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.xml"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.dif"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man sparar XML som DIF med hjälp av Cells Cloud Go-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Go-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen på gång.</li>
<li>Använd metoden `PostWorkbookSaveAs` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>go version go1.13.0 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
