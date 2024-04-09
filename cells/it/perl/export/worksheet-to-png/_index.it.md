---
title:  Esporta FOGLIO DI LAVORO a PNG da Excel utilizzando Cells Cloud SDK per Perl
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Esporta FOGLIO DI LAVORO a PNG da Excel" h2="Libreria Perl per esportare FOGLIO DI LAVORO nel file PNG" p="Utilizza Esporta API di Cells Cloud per esportare i flussi di lavoro degli oggetti interni del file Excel in Perl. Questa è una soluzione professionale per esportare FOGLIO DI LAVORO nel file in formato PNG dal foglio di calcolo online utilizzando Perl." urlsection="export/worksheet-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Esporta l\'oggetto WORKSHEET nel file in formato PNG utilizzando Cells Cloud SDK per Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto FOGLIO DI LAVORO nel file PNG dal file Excel è un'attività complessa. L'esportazione del FOGLIO DI LAVORO nelle transizioni del formato PNG viene eseguita dal nostro SDK Perl mantenendo il contenuto strutturale e logico principale del foglio di lavoro del FOGLIO DI LAVORO di origine. La nostra libreria Perl è una soluzione professionale per esportare oggetti FOGLIO DI LAVORO in file in formato PNG online. Questo Cloud SDK offre agli sviluppatori Perl funzionalità potenti e un output PNG perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice in Perl utilizzando REST API per esportare FOGLIO DI LAVORO nel formato PNG dal foglio di calcolo" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'worksheet',format => 'png');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Perl per esportare oggetti da Excel WORKSHEET a PNG" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Chiama il metodo post_export per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
