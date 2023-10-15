---
title:  Converti BMP in XLTM utilizzando Perl
description:  Utilizzando Aspose.Cells Cloud SDK per Perl per convertire un file in formato BMP in un file in formato XLTM.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Converti BMP in XLTM" h2="Libreria Perl per convertire BMP in XLTM" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Perl. Questa è una soluzione professionale per convertire BMP in XLTM e altri formati di documenti online utilizzando Perl." urlsection="conversion/bmp-to-xltm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti BMP in XLTM utilizzando Cells Cloud SDK per Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da BMP a XLTM può essere un compito complesso. Il nostro SDK Perl gestisce tutte le conversioni dal formato BMP al formato XLTM preservando il contenuto strutturale e logico principale del foglio di calcolo sorgente BMP. La nostra libreria Perl fornisce una soluzione professionale per convertire online file BMP in XLTM. Questo Cloud SDK offre agli sviluppatori Perl potenti funzionalità e garantisce output XLTM di alta qualità.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl Esempio di codice per convertire BMP in XLTM utilizzando Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xltm";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.bmp");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.bmp") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xltm") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare l\'SDK Perl per convertire BMP in XLTM" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Utilizza il metodo `put_convert_workbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
