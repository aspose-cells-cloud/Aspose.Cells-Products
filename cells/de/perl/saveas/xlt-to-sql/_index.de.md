---
title:  Speichern Sie XLT als SQL mit Perl
description:  Verwendung von Aspose.Cells Cloud SDK für Perl zum Speichern von XLT-Formatdateien als SQL-Formatdateien.
kwords: Excel, Save XLT as SQL, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLT as SQL using the Cells Cloud Perl library.","description": "How to save XLT as SQL using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/saveas/xlt-to-sql/","step": [{ "@type": "HowToStep","name": "How to save XLT as SQL using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xlt-to-sql/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLT as SQL using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xlt-to-sql/","text": "Install Perl library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLT as SQL using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xlt-to-sql/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to save XLT as SQL using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xlt-to-sql/","text": "Call post_workbook_save_as method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="XLT als SQL speichern" h2="Perl Bibliothek zum Speichern von XLT als SQL" p="Verwenden Sie SaveAs API von Cells Cloud, um benutzerdefinierte Tabellenkalkulations-Workflows in Perl zu erstellen. Dies ist eine professionelle Lösung, um XLT als SQL und andere Dokumentformate online mit Perl zu speichern." urlsection="saveas/xlt-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="Speichern Sie eine XLT-Datei als SQL unter Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Das Speichern von Dateiformaten aus XLT als SQL ist eine komplexe Aufgabe. Alle XLT-zu-SQL-Formatübergänge werden von unserem SDK Perl durchgeführt, während der strukturelle und logische Hauptinhalt der XLT-Quelltabelle erhalten bleibt. Unsere Perl-Bibliothek ist eine professionelle Lösung, um XLT als SQL-Dateien online zu speichern. Dieses Cloud SDK bietet Perl Entwicklern leistungsstarke Funktionalität und perfekte SQL-Ausgabe.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Codebeispiel zum Speichern von XLT als SQL mit REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.xlt';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.sql';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="So speichern Sie XLT als SQL mithilfe der Cells Cloud Perl-Bibliothek." >}}
<li> Registrieren Sie ein Konto unter<a href="https://dashboard.aspose.cloud/">Armaturenbrett</a> um ein kostenloses API-Kontingent und Autorisierungsdetails zu erhalten</li>
<li>Installieren Sie die Bibliothek Perl und fügen Sie die Referenz (importieren Sie die Bibliothek) zu Ihrem Projekt hinzu.</li>
<li>Öffnen Sie die Quelldatei in Perl.</li>
<li>Beitrag anrufen_Arbeitsmappe_save_as-Methode, um den resultierenden Stream abzurufen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="System Anforderungen" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
