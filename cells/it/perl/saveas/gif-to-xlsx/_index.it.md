---
title:  Salva GIF come XLSX utilizzando Perl
description:  Utilizzando Aspose.Cells Cloud SDK per Perl per salvare il file in formato GIF come file in formato XLSX.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Salva GIF come XLSX" h2="Libreria Perl per salvare GIF come XLSX" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati per fogli di calcolo in Perl. Si tratta di una soluzione professionale per salvare GIF come XLSX e altri formati di documenti online utilizzando Perl." urlsection="saveas/gif-to-xlsx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file GIF come XLSX in Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da GIF come XLSX è un compito complesso. Tutte le transizioni dal formato GIF al formato XLSX vengono eseguite dal nostro SDK Perl mantenendo il contenuto strutturale e logico principale del foglio di calcolo GIF di origine. La nostra libreria Perl è una soluzione professionale per salvare GIF come file XLSX online. Questo Cloud SDK offre agli sviluppatori Perl funzionalità potenti e un output XLSX perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl Codice Esempio per salvare GIF come XLSX utilizzando REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.gif';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.xlsx';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Perl per salvare i file Excel in altri formati GIF come XLSX" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Chiama la posta_cartella di lavoro_save_as per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
