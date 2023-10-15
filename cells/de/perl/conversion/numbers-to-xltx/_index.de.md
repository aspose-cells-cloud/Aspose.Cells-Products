---
title:  Konvertieren Sie NUMBERS mit Perl in XLTX
description:  Verwendung des Aspose.Cells Cloud SDK für Perl zum Konvertieren einer Datei im NUMBERS-Format in eine Datei im XLTX-Format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertieren Sie NUMBERS in XLTX" h2="Perl Bibliothek zum Konvertieren von NUMBERS in XLTX" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Perl-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von NUMBERS in XLTX und andere Dokumentformate unter Perl." urlsection="conversion/numbers-to-xltx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertieren Sie NUMBERS mit dem Cloud SDK Cells für Perl in XLTX" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von NUMBERS in XLTX kann eine komplexe Aufgabe sein. Unser SDK Perl übernimmt alle Konvertierungen von NUMBERS in das XLTX-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der Quelltabelle von NUMBERS bei. Unsere Perl-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von NUMBERS in XLTX-Dateien. Dieses Cloud SDK bietet Perl-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige XLTX-Ausgabe.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl Codebeispiel für die Konvertierung von NUMBERS in XLTX mit Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xltx";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.numbers");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.numbers") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xltx") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie das Perl SDK, um NUMBERS in XLTX zu konvertieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Verwenden Sie die Methode `put_convert_workbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
