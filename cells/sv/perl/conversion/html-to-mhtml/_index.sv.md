---
title:  Konvertera HTML till MHTML med Perl
description:  Använda Aspose.Cells Cloud SDK för Perl för att konvertera en fil i HTML-format till en fil i MHTML-format.
kwords: Excel, Convert HTML to MHTML, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert HTML to MHTML using the Cells Cloud Perl library.","description": "How to convert HTML to MHTML using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/conversion/html-to-mhtml/","step": [{ "@type": "HowToStep","name": "How to convert HTML to MHTML using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/html-to-mhtml/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert HTML to MHTML using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/html-to-mhtml/","text": "Install Perl package and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert HTML to MHTML using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/html-to-mhtml/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to convert HTML to MHTML using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/html-to-mhtml/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera HTML till MHTML" h2="Perl bibliotek för att konvertera HTML till MHTML" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Perl projekt. Detta är en professionell lösning för att konvertera HTML till MHTML och andra dokumentformat online med Perl." urlsection="conversion/html-to-mhtml/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera HTML till MHTML med Cells Cloud SDK för Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från HTML till MHTML kan vara en komplex uppgift. Vår Perl SDK hanterar alla konverteringar från HTML till MHTML-format samtidigt som det huvudsakliga strukturella och logiska innehållet i källarket HTML bevaras. Vårt Perl-bibliotek tillhandahåller en professionell lösning för att konvertera HTML till MHTML-filer online. Denna Cloud SDK ger Perl utvecklare kraftfull funktionalitet och säkerställer högkvalitativa MHTML-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Kodexempel för att konvertera HTML till MHTML med Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "mhtml";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.html");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.html") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.mhtml") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man konverterar HTML till MHTML med hjälp av Cells Cloud Perl-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera paketet Perl och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Perl.</li>
<li>Använd metoden `put_convert_workbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
