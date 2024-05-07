---
title:  Spara TXT som BMP med Perl
description:  Använder Aspose.Cells Cloud SDK för Perl för att spara fil i TXT-format som fil i BMP-format.
kwords: Excel, Save TXT as BMP, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save TXT as BMP using the Cells Cloud Perl library.","description": "How to save TXT as BMP using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/saveas/txt-to-bmp/","step": [{ "@type": "HowToStep","name": "How to save TXT as BMP using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/txt-to-bmp/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save TXT as BMP using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/txt-to-bmp/","text": "Install Perl library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save TXT as BMP using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/txt-to-bmp/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to save TXT as BMP using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/txt-to-bmp/","text": "Call post_workbook_save_as method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Spara TXT som BMP" h2="Perl bibliotek för att spara TXT som BMP" p="Använd SaveAs API av Cells Cloud för att skapa anpassade arbetsflöden för kalkylblad i Perl. Detta är en professionell lösning för att spara TXT som BMP och andra dokumentformat online med Perl." urlsection="saveas/txt-to-bmp/" >}}

{{< blocks/products/cells/cells-cloud-section title="Spara en TXT-fil som BMP i Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från TXT som BMP är en komplex uppgift. Alla formatövergångar från TXT till BMP utförs av vår Perl SDK samtidigt som källkodens TXT-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Perl-bibliotek är en professionell lösning för att spara TXT som BMP-filer online. Denna Cloud SDK ger Perl-utvecklare kraftfull funktionalitet och perfekt BMP-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Kod Exempel för att spara TXT som BMP med REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.txt';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.bmp';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man sparar TXT som BMP med Cells Cloud Perl-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Perl-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Perl.</li>
<li>Ring post_arbetsbok_save_as-metoden för att hämta den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
