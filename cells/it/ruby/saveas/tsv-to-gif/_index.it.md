﻿---
title:  Salva TSV come GIF API per Ruby
description:  API cloud e SDK per Microsoft Excel e OpenOffice Calc. Converti foglio di calcolo in un altro file di formato.
url: /it/ruby/saveas/tsv-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API per salvare TSV come GIF" h2="Libreria Ruby per salvare TSV come GIF" p="Usa Cells SaveAs REST API per creare flussi di lavoro di fogli di calcolo personalizzati in Ruby. Questa è una soluzione professionale per salvare TSV come GIF e altri formati di documenti online utilizzando Ruby." urlsection="saveas/tsv-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Salva un file TSV come GIF in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da TSV come GIF è un compito complesso. Tutte le transizioni dal formato TSV al formato GIF vengono eseguite dal nostro SDK Ruby mantenendo il contenuto strutturale e logico principale del foglio di calcolo TSV di origine. La nostra libreria Ruby è una soluzione professionale per salvare TSV come file GIF online. Questo Cloud SDK offre agli sviluppatori Ruby potenti funzionalità e un perfetto output GIF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Ruby utilizzando REST API per salvare TSV come formato GIF" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.tsv'
    save_options = nil
    newfilename = 'Book1Saveas.gif'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Ruby API per salvare TSV come GIF" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama celle_salva_COME_inviare_documento_salva_come metodo per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>rubino 2.5 o più recente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}