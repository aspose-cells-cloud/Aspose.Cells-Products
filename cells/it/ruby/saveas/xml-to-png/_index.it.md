---
title:  Salva XML come PNG utilizzando Ruby
description:  Utilizzando Aspose.Cells Cloud SDK per Ruby per salvare il file in formato XML come file in formato PNG.
kwords: Excel, Save XML as PNG, REST, Ruby
howto: How to save XML as PNG using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Salva XML come PNG" h2="Libreria Ruby per salvare XML come PNG" p="Utilizza SaveAs API di Cells Cloud per creare flussi di lavoro personalizzati per fogli di calcolo in Ruby. Questa è una soluzione professionale per salvare XML come PNG e altri formati di documenti online utilizzando Ruby." urlsection="saveas/xml-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Salva un file XML come PNG in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Salvare i formati di file da XML come PNG è un compito complesso. Tutte le transizioni dal formato XML al formato PNG vengono eseguite dal nostro SDK Ruby mantenendo il contenuto strutturale e logico principale del foglio di calcolo XML di origine. La nostra libreria Ruby è una soluzione professionale per salvare online XML come file PNG. Questo Cloud SDK offre agli sviluppatori Ruby funzionalità potenti e un output PNG perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice Ruby per salvare XML come PNG utilizzando REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.xml'
    save_options = nil
    newfilename = 'Book1Saveas.png'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Scopri come salvare XML come PNG utilizzando la libreria Cloud Ruby Cells." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Ruby e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in Ruby.</li>
<li>Utilizza il metodo `post_workbook_save_as` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>rubino 2.5 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
