﻿---
title:  JSON in HTML Converti API in Perl
description:  API cloud e SDK per Microsoft Excel e OpenOffice Calc. Converti foglio di calcolo in un altro file di formato.
url: /it/perl/conversion/json-to-html/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API per convertire JSON in HTML" h2="Perl libreria per convertire JSON in HTML" p="Usa Cells Conversion REST API per creare flussi di lavoro di fogli di calcolo personalizzati in Perl. Questa è una soluzione professionale per convertire JSON in HTML e altri formati di documenti online utilizzando Perl." urlsection="conversion/json-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti un file JSON in HTML in Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da JSON a HTML è un'attività complessa. Tutte le transizioni di formato da JSON a HTML vengono eseguite dal nostro SDK Perl mantenendo il contenuto strutturale e logico principale del foglio di calcolo JSON di origine. La nostra libreria Perl è una soluzione professionale per convertire file JSON in HTML online. Questo Cloud SDK offre agli sviluppatori Perl potenti funzionalità e un output HTML perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Perl utilizzando REST API per convertire JSON nel formato HTML" gistPath="" %}}
 
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
    my @fileinfos = stat("Book1.json");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.json") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.html") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Perl API per convertire JSON in HTML" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama celle_cartella di lavoro_Mettere_convertire_metodo della cartella di lavoro per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}