---
title: Exportieren Sie LISTOBJECT von Excel nach PDF mit dem Cloud SDK Cells für Perl
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportieren Sie LISTOBJECT von Excel nach PDF" h2="Perl-Bibliothek zum Exportieren von LISTOBJECT in die Datei PDF" p="Verwenden Sie Export API von Cells Cloud, um Excel-Datei-interne Objekt-Workflows in Perl zu exportieren. Dies ist eine professionelle Lösung, um LISTOBJECT in eine PDF-Formatdatei aus einer Tabellenkalkulation online mit Perl zu exportieren." urlsection="export/listobject-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportieren Sie das LISTOBJECT-Objekt in die Formatdatei PDF mit dem Cloud SDK Cells für Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren des LISTOBJECT-Objekts aus der Datei Excel in die Datei PDF ist eine komplexe Aufgabe. Der Export von LISTOBJECT-Formatübergängen in das PDF-Format wird von unserem Perl-SDK durchgeführt, während der strukturelle und logische Hauptinhalt der Quell-LISTOBJECT-Tabelle erhalten bleibt. Unsere Perl-Bibliothek ist eine professionelle Lösung zum Online-Export von LISTOBJECT-Objekten in Dateien im PDF-Format. Dieses Cloud SDK bietet Perl Entwicklern leistungsstarke Funktionalität und eine perfekte PDF Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Codebeispiel in Perl mit REST API zum Exportieren von LISTOBJECT in das PDF-Format aus der Tabellenkalkulation" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'listobject',format => 'pdf');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für Perl, um Objekte von Excel LISTOBJECT nach PDF zu exportieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Rufen Sie die Methode post_export auf, um den resultierenden Stream zu erhalten</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
