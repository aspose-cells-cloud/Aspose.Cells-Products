---
title:  Konvertera XLS till HTML med C#
description:  Använda Aspose.Cells Cloud SDK för C# för att konvertera en fil i XLS-format till en fil i HTML-format.
kwords: Excel, Convert XLS to HTML, REST, C#
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLS to HTML using the Cells Cloud Net library.","description": "How to convert XLS to HTML using the Cells Cloud Net library.","image": {"@type": "ImageObject"},"url": "/net/conversion/xls-to-html/","step": [{ "@type": "HowToStep","name": "How to convert XLS to HTML using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/conversion/xls-to-html/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLS to HTML using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/conversion/xls-to-html/","text": "Install C# library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLS to HTML using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/conversion/xls-to-html/","text": "Open the source file in C#",},{ "@type": "HowToStep","name": "How to convert XLS to HTML using the Cells Cloud Net library. step 1", "image": {"@type": "ImageObject",},"url": "/net/conversion/xls-to-html/","text": "Use the `PutConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider "},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera XLS till HTML" h2="C# bibliotek för att konvertera XLS till HTML" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Net-projekt. Detta är en professionell lösning för att konvertera XLS till HTML och andra dokumentformat online med C#." urlsection="conversion/xls-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera XLS till HTML med Cells Cloud SDK för C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLS till HTML kan vara en komplicerad uppgift. Vår C# SDK hanterar alla XLS- till HTML-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i käll-XLS-kalkylarket bevaras. Vårt C#-bibliotek tillhandahåller en professionell lösning för att konvertera XLS till HTML-filer online. Denna Cloud SDK ger C#-utvecklare kraftfull funktionalitet och säkerställer högkvalitativa HTML-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Kod Exempel för att konvertera XLS till HTML med Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xls";
    string format = "html";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.html";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man konverterar XLS till HTML med hjälp av Cells Cloud Net-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera C#-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i C#</li>
<li>Använd metoden `PutConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>NET Framework 4.5.2 eller senare</li>
<li>Net Standard 2.0 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
