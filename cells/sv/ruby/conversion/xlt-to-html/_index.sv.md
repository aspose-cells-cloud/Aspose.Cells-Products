---
title: Konvertera XLT till HTML med Ruby
description:  Använda Aspose.Cells Cloud SDK för Ruby för att konvertera en fil i XLT-format till en fil i HTML-format.
kwords: Excel, Convert XLT to HTML, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLT to HTML using the Cells Cloud Ruby library.","description": "How to convert XLT to HTML using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/conversion/xlt-to-html/","step": [{ "@type": "HowToStep","name": "How to convert XLT to HTML using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/xlt-to-html/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLT to HTML using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/xlt-to-html/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLT to HTML using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/xlt-to-html/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to convert XLT to HTML using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/xlt-to-html/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera XLT till HTML" h2="Ruby-bibliotek för att konvertera XLT till HTML" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Ruby-projekt. Detta är en professionell lösning för att konvertera XLT till HTML och andra dokumentformat online med Ruby." urlsection="conversion/xlt-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera XLT till HTML med Cells Cloud SDK för Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLT till HTML kan vara en komplicerad uppgift. Vår Ruby SDK hanterar alla XLT- till HTML-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i käll-XLT-kalkylarket bevaras. Vårt Ruby-bibliotek tillhandahåller en professionell lösning för att konvertera XLT till HTML-filer online. Denna Cloud SDK ger Ruby-utvecklare kraftfull funktionalitet och säkerställer högkvalitativa HTML-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby Code Exempel för att konvertera XLT till HTML med Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xlt"
            format = 'html'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man konverterar XLT till HTML med hjälp av Cells Cloud Ruby-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Ruby-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Ruby.</li>
<li>Använd metoden `put_convert_workbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>ruby 2.5 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
