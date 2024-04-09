---
title:  Converti FODS in TIFF usando Ruby
description: Utilizzando Aspose.Cells Cloud SDK per Ruby per convertire un file in formato FODS in un file in formato TIFF.
kwords: Excel, Convert FODS to TIFF, REST, Ruby
howto: How to convert FODS to TIFF using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Converti FODS in TIFF" h2="Libreria Ruby per convertire FODS in TIFF" p="Utilizza la conversione API di Cells Cloud per creare flussi di lavoro personalizzati con fogli di calcolo nei progetti Ruby. Questa è una soluzione professionale per convertire FODS in TIFF e altri formati di documenti online utilizzando Ruby." urlsection="conversion/fods-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Converti FODS in TIFF utilizzando Cells Cloud SDK per Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da FODS a TIFF può essere un compito complesso. Il nostro SDK Ruby gestisce tutte le conversioni del formato FODS in TIFF preservando il contenuto strutturale e logico principale del foglio di calcolo FODS di origine. La nostra libreria Ruby fornisce una soluzione professionale per convertire file FODS in TIFF online. Questo Cloud SDK offre agli sviluppatori Ruby funzionalità potenti e garantisce un output TIFF di alta qualità.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice Ruby per convertire FODS in TIFF utilizzando Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.fods"
            format = 'tiff'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Scopri come convertire FODS in TIFF utilizzando la libreria Cells Cloud Ruby." >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Installa la libreria Ruby e aggiungi il riferimento (importa la libreria) al tuo progetto.</li>
<li>Apri il file sorgente in Ruby.</li>
<li>Utilizza il metodo `put_convert_workbook` per recuperare il flusso risultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>rubino 2.5 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
