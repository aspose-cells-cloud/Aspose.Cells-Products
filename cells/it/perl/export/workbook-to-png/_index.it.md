---
title:  Esporta cartella di lavoro a PNG da Excel utilizzando Cells Cloud SDK per Perl
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
kwords: Excel, workbook, png, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to PNG","description": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to PNG","image": {"@type": "ImageObject"},"url": "/perl/export/workbook-to-png/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to PNG step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/workbook-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to PNG step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/workbook-to-png/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to PNG step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/workbook-to-png/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Esporta cartella di lavoro a PNG da Excel" h2="Libreria Perl per esportare WORKBOOK nel file PNG" p="Utilizzare Esporta API di Cells Cloud per esportare i flussi di lavoro degli oggetti interni del file Excel in Perl. Si tratta di una soluzione professionale per esportare la cartella di lavoro nel file in formato PNG dal foglio di calcolo online utilizzando Perl." urlsection="export/workbook-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Esporta l\'oggetto WORKBOOK nel file in formato PNG utilizzando Cells Cloud SDK per Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto WORKBOOK nel file PNG dal file Excel è un'attività complessa. L'esportazione della cartella di lavoro nelle transizioni del formato PNG viene eseguita dal nostro SDK Perl mantenendo il contenuto strutturale e logico principale del foglio di calcolo della cartella di lavoro di origine. La nostra libreria Perl è una soluzione professionale per esportare online oggetti WORKBOOK in file in formato PNG. Questo Cloud SDK offre agli sviluppatori Perl funzionalità potenti e un output PNG perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice in Perl utilizzando REST API per esportare WORKBOOK nel formato PNG dal foglio di calcolo" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'workbook',format => 'png');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Perl per esportare oggetti da Excel WORKBOOK a PNG" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Chiama il metodo post_export per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
