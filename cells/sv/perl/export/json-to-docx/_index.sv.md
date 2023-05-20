---
title: Exportera Json till DOCX-fil via Perl
description: Aspose.Cells Cloud REST API stöder export av Excel-filer och interna objekt till olika formatfiler. SDK stöder olika utvecklingsspråk. De inkluderar Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby och swift.
url: /sv/perl/export/json-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Exportera JSON till DOCX-fil i molnet" h2="Excel & OpenOffice-kalkylbladsexport med open source Cloud SDK för Perl" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=" Exoprera JSON till DOCX-fil i Cloud SDK för Perl" %}}
1.  Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation
1. Initiera ```CellsApi``` med klient-id, klienthemlighet, basadress och API-version
1. Ring ```cells_workbook_put_convert_workbook```-metoden för att få den resulterande DOCX-strömmen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Kom igång med Excel REST API" %}}
 Få Excel Cloud SDK for .NET källkod från[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl) för att kompilera SDK själv eller gå till[Släpps](https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/releases) för alternativa nedladdningsalternativ.

 Ta också en titt på Swagger-baserad[API Referens]() att veta mer om[Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Perl Kod för JSON till DOCX-konvertering" gistPath="" %}}
```perl
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "docx";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xlsx");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xlsx") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.docx") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
