---
title:  Konvertera FODS till TSV med Perl
description:  Använder Aspose.Cells Cloud SDK för Perl för att konvertera en fil i FODS-format till en fil i TSV-format.
kwords: Excel, Convert FODS to TSV, REST, Perl
howto: How to convert FODS to TSV using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera FODS till TSV" h2="Perl bibliotek för konvertering av FODS till TSV" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Perl projekt. Detta är en professionell lösning för att konvertera FODS till TSV och andra dokumentformat online med Perl." urlsection="conversion/fods-to-tsv/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera FODS till TSV med Cells Cloud SDK för Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från FODS till TSV kan vara en komplex uppgift. Vårt Perl SDK hanterar alla FODS- till TSV-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i FODS-källbladet bevaras. Vårt Perl-bibliotek tillhandahåller en professionell lösning för att konvertera FODS till TSV-filer online. Denna Cloud SDK ger Perl utvecklare kraftfull funktionalitet och säkerställer högkvalitativa TSV-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Kodexempel för att konvertera FODS till TSV med Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "tsv";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.fods");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.fods") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.tsv") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Lär dig hur du konverterar FODS till TSV med hjälp av Cells Cloud Perl-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera paketet Perl och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Perl.</li>
<li>Använd metoden `put_convert_workbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
