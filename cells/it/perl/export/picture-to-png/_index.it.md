---
title:  Esporta IMMAGINE in PNG dal foglio di calcolo utilizzando Perl API
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
url: /it/perl/export/picture-to-png/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API per esportare l\'IMMAGINE nel file PNG" h2="Perl per esportare l\'IMMAGINE nel file PNG" p="Utilizzare Cells Export REST API per esportare i flussi di lavoro degli oggetti interni del foglio di calcolo in Perl. Questa è una soluzione professionale per esportare l\'IMMAGINE nel file in formato PNG dal foglio di calcolo online utilizzando Perl." urlsection="export/picture-to-png/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Esporta l\'oggetto IMMAGINE nel file in formato PNG in Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto PICTURE nel file PNG dal foglio di calcolo è un'attività complessa. L'esportazione delle transizioni di formato da IMMAGINE a PNG viene eseguita dal nostro SDK Perl mantenendo il contenuto strutturale e logico principale del foglio di calcolo IMMAGINE di origine. La nostra libreria Perl è una soluzione professionale per esportare oggetti PICTURE in file in formato PNG online. Questo Cloud SDK offre agli sviluppatori Perl potenti funzionalità e un output PNG perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Perl utilizzando REST API per esportare IMMAGINE nel formato PNG dal foglio di calcolo" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'picture',format => 'png');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Perl API per esportare IMMAGINE a PNG" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo post_export per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
