---
title:  Konvertieren Sie XLT mit Perl in JSON
description:  Verwendung des Cloud SDK Aspose.Cells für Perl zum Konvertieren einer Datei im XLT-Format in eine Datei im JSON-Format.
kwords: Excel, Convert XLT to JSON, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLT to JSON using the Cells Cloud Perl library.","description": "How to convert XLT to JSON using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/conversion/xlt-to-json/","step": [{ "@type": "HowToStep","name": "How to convert XLT to JSON using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlt-to-json/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLT to JSON using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlt-to-json/","text": "Install Perl package and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLT to JSON using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlt-to-json/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to convert XLT to JSON using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlt-to-json/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie XLT in JSON" h2="Perl Bibliothek zum Konvertieren von XLT in JSON" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Perl-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XLT in JSON und andere Dokumentformate unter Perl." urlsection="conversion/xlt-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie XLT in JSON mit dem Cloud SDK Cells für Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLT in JSON kann eine komplexe Aufgabe sein. Unser Perl SDK übernimmt alle XLT-in-JSON-Formatkonvertierungen und behält dabei den wichtigsten strukturellen und logischen Inhalt der XLT-Quelltabelle bei. Unsere Perl-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von XLT- in JSON-Dateien. Dieses Cloud SDK bietet Perl-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige JSON-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Codebeispiel für die Konvertierung von XLT in JSON mit Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "json";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xlt");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xlt") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.json") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So konvertieren Sie XLT mit der Cells Cloud Perl-Bibliothek in JSON." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie das Paket Perl und fügen Sie Ihrem Projekt die Referenz hinzu (importieren Sie die Bibliothek).</li>
<li>Öffnen Sie die Quelldatei in Perl.</li>
<li>Verwenden Sie die Methode `put_convert_workbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
