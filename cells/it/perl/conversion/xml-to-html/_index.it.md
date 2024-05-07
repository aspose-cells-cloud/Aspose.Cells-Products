---
title:  Converti XML in HTML utilizzando Perl
description:  Utilizzando Aspose.Cells Cloud SDK per Perl per convertire un file in formato XML in un file in formato HTML.
kwords: Excel, Convert XML to HTML, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert XML to HTML using the Cells Cloud Perl library.","description": "How to convert XML to HTML using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/conversion/xml-to-html/","step": [{ "@type": "HowToStep","name": "How to convert XML to HTML using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xml-to-html/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert XML to HTML using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xml-to-html/","text": "Install Perl package and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert XML to HTML using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xml-to-html/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to convert XML to HTML using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/xml-to-html/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti XML in HTML" h2="Libreria Perl per convertire XML in HTML" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Perl. Questa è una soluzione professionale per convertire XML in HTML e altri formati di documenti online utilizzando Perl." urlsection="conversion/xml-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti XML in HTML utilizzando Cells Cloud SDK per Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da XML a HTML può essere un compito complesso. Il nostro SDK Perl gestisce tutte le conversioni del formato XML in HTML preservando il contenuto strutturale e logico principale del foglio di calcolo XML di origine. La nostra libreria Perl fornisce una soluzione professionale per convertire file XML in HTML online. Questo Cloud SDK offre agli sviluppatori Perl potenti funzionalità e garantisce un output HTML di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Esempio di codice per convertire XML in HTML utilizzando Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "html";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xml");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xml") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.html") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come convertire XML in HTML utilizzando la libreria Cells Cloud Perl." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa il pacchetto Perl e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in Perl.</li>
<li>Utilizza il metodo `put_convert_workbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
