---
title:  Exportera LISTOBJECT till GIF från Excel med Cells Cloud SDK för Perl
description:  Aspose.Cells Cloud REST API stöder export av filer från {0} till {1}-format med {2}.
kwords: Excel, listobject, gif, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to GIF","description": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to GIF","image": {"@type": "ImageObject"},"url": "/perl/export/listobject-to-gif/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to GIF step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/listobject-to-gif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to GIF step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/listobject-to-gif/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to GIF step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/listobject-to-gif/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportera LISTOBJECT till GIF från Excel" h2="Perl bibliotek för export av LISTOBJECT till GIF-fil" p="Använd Export API av Cells Cloud för att exportera Excel fil interna objekt arbetsflöden i Perl. Detta är en professionell lösning för att exportera LISTOBJECT till GIF-format fil från kalkylblad online med Perl." urlsection="export/listobject-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportera LISTOBJECT-objekt till GIF-formatfil med Cells Cloud SDK för Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportera LISTOBJECT-objekt till GIF-fil från Excel-filen är en komplex uppgift. Export av LISTOBJECT till GIF-formatövergångar utförs av vår Perl SDK samtidigt som källbladets LISTOBJECT-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Perl-bibliotek är en professionell lösning för att exportera LISTOBJECT-objekt till GIF-formatfiler online. Denna Cloud SDK ger Perl utvecklare kraftfull funktionalitet och perfekt GIF-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Kodexempel i Perl med REST API för att exportera LISTOBJECT till GIF-format från kalkylark" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use MIME::Base64;
    use AsposeCellsCloud::LightCellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::LightCellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $filemap = { 'Book1.xlsx' => '~/TestData/Book1.xlsx', 'myDocument.xlsx' => ~/TestData/myDocument.xlsx'};
    my $result = $instance->post_export(file => $filemap , object_type => 'listobject',format => 'gif');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för Perl för att exportera objekt från Excel LISTOBJECT till GIF" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Anrop post_export-metoden för att hämta den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
