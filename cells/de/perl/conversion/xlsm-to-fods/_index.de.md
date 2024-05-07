---
title:  Konvertieren Sie XLSM mit Perl in FODS
description:  Verwendung des Aspose.Cells Cloud SDK für Perl zum Konvertieren einer XLSM-Formatdatei in eine FODS-Formatdatei.
kwords: Excel, Convert XLSM to FODS, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XLSM to FODS using the Cells Cloud Perl library.","description": "How to convert XLSM to FODS using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/conversion/xlsm-to-fods/","step": [{ "@type": "HowToStep","name": "How to convert XLSM to FODS using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlsm-to-fods/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XLSM to FODS using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlsm-to-fods/","text": "Install Perl package and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XLSM to FODS using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlsm-to-fods/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to convert XLSM to FODS using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xlsm-to-fods/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertieren Sie XLSM in FODS" h2="Perl Bibliothek zur Konvertierung von XLSM in FODS" p="Verwenden Sie die Konvertierung API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Perl-Projekten zu erstellen. Dies ist eine professionelle Lösung zum Online-Konvertieren von XLSM in FODS und andere Dokumentformate unter Perl." urlsection="conversion/xlsm-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertieren Sie XLSM in FODS mit dem Cloud SDK Cells für Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Das Konvertieren von Dateiformaten von XLSM in FODS kann eine komplexe Aufgabe sein. Unser Perl SDK übernimmt alle Konvertierungen von XLSM in das FODS-Format und behält dabei den wichtigsten strukturellen und logischen Inhalt der XLSM-Quelltabelle bei. Unsere Perl-Bibliothek bietet eine professionelle Lösung für die Online-Konvertierung von XLSM- in FODS-Dateien. Dieses Cloud SDK bietet Perl-Entwicklern leistungsstarke Funktionen und gewährleistet eine hochwertige FODS-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Codebeispiel für die Konvertierung von XLSM in FODS mit Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "fods";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xlsm");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xlsm") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.fods") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So konvertieren Sie XLSM mithilfe der Cells Cloud Perl-Bibliothek in FODS." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie das Paket Perl und fügen Sie Ihrem Projekt die Referenz hinzu (importieren Sie die Bibliothek).</li>
<li>Öffnen Sie die Quelldatei in Perl.</li>
<li>Verwenden Sie die Methode `put_convert_workbook`, um den resultierenden Stream abzurufen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
