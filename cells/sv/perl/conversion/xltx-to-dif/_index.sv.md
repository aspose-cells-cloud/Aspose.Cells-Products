﻿---
title:  XLTX till DIF Konvertera API för Perl
description:  Använder Aspose.Cells Cloud SDK för Perl för att konvertera XLTX-formatfil till DIF-formatfil.
url: /sv/perl/conversion/xltx-to-dif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API för att konvertera XLTX till DIF" h2="Perl bibliotek för att konvertera XLTX till DIF" p="Använd Cells Conversion REST API för att skapa anpassade arbetsflöden för kalkylblad i Perl. Detta är en professionell lösning för att konvertera XLTX till DIF och andra dokumentformat online med Perl." urlsection="conversion/xltx-to-dif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera en XLTX-fil till DIF i Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLTX till DIF är en komplex uppgift. Alla XLTX- till DIF-formatövergångar utförs av vår Perl SDK samtidigt som källbladets XLTX-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Perl-bibliotek är en professionell lösning för att konvertera XLTX till DIF-filer online. Denna Cloud SDK ger Perl utvecklare kraftfull funktionalitet och perfekt DIF-utgång.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Perl med REST API för att konvertera XLTX till DIF-format" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "dif";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xltx");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xltx") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.dif") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Perl API för att konvertera XLTX till DIF" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Ring celler_arbetsbok_sätta_konvertera_arbetsboksmetod för att få den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}