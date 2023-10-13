﻿---
title:  Spara TXT som HTML API för Perl
description:  Använder Aspose.Cells Cloud SDK för Perl för att spara TXT-formatfilen som HTML-formatfil.
url: /sv/perl/saveas/txt-to-html/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API för att spara TXT som HTML" h2="Perl bibliotek för att spara TXT som HTML" p="Använd Cells SaveAs REST API för att skapa anpassade arbetsflöden för kalkylblad i Perl. Detta är en professionell lösning för att spara TXT som HTML och andra dokumentformat online med Perl." urlsection="saveas/txt-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en TXT-fil som HTML i Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från TXT som HTML är en komplex uppgift. Alla formatövergångar från TXT till HTML utförs av vår Perl SDK samtidigt som källkodens TXT-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Perl-bibliotek är en professionell lösning för att spara TXT som HTML-filer online. Denna Cloud SDK ger Perl-utvecklare kraftfull funktionalitet och perfekt HTML-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Perl med REST API för att spara TXT som HTML-format" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.txt';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.html';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Perl API för att spara TXT som HTML" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Ring celler_spara_som_posta_dokumentera_spara_som metod för att få den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}