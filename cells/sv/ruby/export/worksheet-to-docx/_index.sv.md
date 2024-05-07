---
title:  Exportera ARBETSBLAD till DOCX från Excel med Cells Cloud SDK för Ruby
description:  Aspose.Cells Cloud REST API stöder export av filer från {0} till {1}-format med {2}.
kwords: Excel, worksheet, docx, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to DOCX","description": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to DOCX","image": {"@type": "ImageObject"},"url": "/ruby/export/worksheet-to-docx/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to DOCX step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/worksheet-to-docx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to DOCX step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/worksheet-to-docx/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to DOCX step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/worksheet-to-docx/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportera ARBETSBLAD till DOCX från Excel" h2="Ruby bibliotek för export av WORKSHEET till DOCX-fil" p="Använd Exportera API av Cells Cloud för att exportera Excel filinterna objektarbetsflöden i Ruby. Detta är en professionell lösning för att exportera ARBETSBLAD till DOCX-formatfil från kalkylblad online med Ruby." urlsection="export/worksheet-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportera WORKSHEET-objekt till DOCX-formatfil med Cells Cloud SDK för Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportera WORKSHEET-objekt till DOCX-fil från Excel-filen är en komplex uppgift. Exportera ARBETSBLAD till DOCX-formatövergångar utförs av vår Ruby SDK samtidigt som källarbetsbladets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Ruby-bibliotek är en professionell lösning för att exportera WORKSHEET-objekt till DOCX-formatfiler online. Denna Cloud SDK ger Ruby-utvecklare kraftfull funktionalitet och perfekt DOCX-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Kodexempel i Ruby som använder REST API för att exportera ARBETSBLAD till DOCX-format från kalkylblad" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::LiteCellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            files = {}      
            name = $DataSourceXlsx
            files[name] = ::File.open(File.expand_path("data/"+name),"r") 
            name =$AssemblyTestXlsx 
            files[name] = ::File.open(File.expand_path("data/"+name),"r")
            format = 'docx'
            objectType =  'worksheet'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för Ruby för att exportera objekt från Excel WORKSHEET till DOCX" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Anrop post_export-metoden för att hämta den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>ruby 2.5 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
