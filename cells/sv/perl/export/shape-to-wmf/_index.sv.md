---
title:  Exportera SHAPE till WMF från Excel med Cells Cloud SDK för Perl
description:  Aspose.Cells Cloud REST API stöder export av filer från {0} till {1}-format med {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportera SHAPE till WMF från Excel" h2="Perl-bibliotek för att exportera SHAPE till WMF-fil" p="Använd Export API av Cells Cloud för att exportera Excel fil interna objekt arbetsflöden i Perl. Detta är en professionell lösning för att exportera SHAPE till WMF-format fil från kalkylblad online med Perl." urlsection="export/shape-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportera SHAPE-objekt till WMF-formatfil med Cells Cloud SDK för Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportera SHAPE-objekt till WMF-fil från Excel-filen är en komplex uppgift. Export av SHAPE till WMF-formatövergångar utförs av vår Perl SDK med bibehållen källans SHAPE-kalkylblads huvudsakliga strukturella och logiska innehåll. Vårt Perl-bibliotek är en professionell lösning för att exportera SHAPE-objekt till WMF-formatfiler online. Denna Cloud SDK ger Perl utvecklare kraftfull funktionalitet och perfekt WMF-utgång.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Kodexempel i Perl med REST API för att exportera SHAPE till WMF-format från kalkylark" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'shape',format => 'wmf');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för Perl för att exportera objekt från Excel SHAPE till WMF" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Anrop post_export-metoden för att hämta den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
