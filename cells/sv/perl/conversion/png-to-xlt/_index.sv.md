---
title:  Konvertera PNG till XLT med Perl
description:  Använda Aspose.Cells Cloud SDK för Perl för att konvertera en fil i PNG-format till en XLT-fil.
kwords: Excel, Convert PNG to XLT, REST, Perl
howto: How to convert PNG to XLT using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera PNG till XLT" h2="Perl bibliotek för att konvertera PNG till XLT" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Perl projekt. Detta är en professionell lösning för att konvertera PNG till XLT och andra dokumentformat online med Perl." urlsection="conversion/png-to-xlt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera PNG till XLT med Cells Cloud SDK för Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från PNG till XLT kan vara en komplicerad uppgift. Vår Perl SDK hanterar alla konverteringar från PNG till XLT-format samtidigt som det huvudsakliga strukturella och logiska innehållet i källarket PNG bevaras. Vårt Perl-bibliotek tillhandahåller en professionell lösning för att konvertera PNG till XLT-filer online. Denna Cloud SDK ger Perl utvecklare kraftfull funktionalitet och säkerställer högkvalitativ XLT-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Kod Exempel för att konvertera PNG till XLT med Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xlt";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.png");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.png") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xlt") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Lär dig hur du konverterar PNG till XLT med hjälp av Cells Cloud Perl-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera paketet Perl och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Perl.</li>
<li>Använd metoden `put_convert_workbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
