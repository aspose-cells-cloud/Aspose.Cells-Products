---
title:  Exportieren Sie LISTOBJECT von Excel nach JSON mit dem Cloud SDK Cells für Perl
description:  Aspose.Cells Cloud REST API unterstützt den Export von Dateien im {0}-Format in {1} mit {2}.
kwords: Excel, listobject, json, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to JSON","description": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to JSON","image": {"@type": "ImageObject"},"url": "/perl/export/listobject-to-json/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to JSON step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/listobject-to-json/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to JSON step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/listobject-to-json/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to JSON step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/listobject-to-json/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportieren Sie LISTOBJECT von Excel nach JSON" h2="Perl Bibliothek zum Exportieren von LISTOBJECT in eine JSON-Datei" p="Verwenden Sie Export API von Cells Cloud, um Excel Datei-interne Objekt-Workflows in Perl zu exportieren. Dies ist eine professionelle Lösung, um LISTOBJECT online aus einer Tabellenkalkulation in eine JSON-Formatdatei mit Perl zu exportieren." urlsection="export/listobject-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportieren Sie das LISTOBJECT-Objekt in eine Datei im JSON-Format mit dem Cloud SDK Cells für Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Das Exportieren eines LISTOBJECT-Objekts aus der Datei Excel in eine JSON-Datei ist eine komplexe Aufgabe. Der Export von LISTOBJECT-Formatübergängen in das JSON-Format wird von unserem SDK Perl durchgeführt, während der strukturelle und logische Hauptinhalt der Quell-LISTOBJECT-Tabelle erhalten bleibt. Unsere Bibliothek Perl ist eine professionelle Lösung zum Online-Export von LISTOBJECT-Objekten in Dateien im JSON-Format. Dieses Cloud SDK bietet Perl Entwicklern leistungsstarke Funktionalität und perfekte JSON-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Codebeispiel in Perl mit REST API zum Exportieren von LISTOBJECT in das JSON-Format aus einer Tabellenkalkulation" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'listobject',format => 'json');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So verwenden Sie Cells Cloud SDK für Perl, um Objekte von Excel LISTOBJECT nach JSON zu exportieren" >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Initialisieren Sie Cells API mit Ihrer Client-ID, Ihrem Client-Geheimnis, Ihrer Basis-URL und Ihrer Version API.</li>
<li>Rufen Sie die Methode post_export auf, um den resultierenden Stream zu erhalten</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
