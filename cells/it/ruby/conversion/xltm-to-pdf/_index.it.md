﻿---
title:  XLTM in PDF Converti API per Ruby
description:  API cloud e SDK per Microsoft Excel e OpenOffice Calc. Converti foglio di calcolo in un altro file di formato.
url: /it/ruby/conversion/xltm-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API per convertire XLTM in PDF" h2="Libreria Ruby per convertire XLTM in PDF" p="Usa Cells Conversion REST API per creare flussi di lavoro di fogli di calcolo personalizzati in Ruby. Questa è una soluzione professionale per convertire XLTM in PDF e altri formati di documenti online utilizzando Ruby." urlsection="conversion/xltm-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Converti un file XLTM in PDF in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversione dei formati di file da XLTM a PDF è un'operazione complessa. Tutte le transizioni di formato da XLTM a PDF vengono eseguite dal nostro SDK Ruby mantenendo il contenuto strutturale e logico principale del foglio di calcolo XLTM di origine. La nostra libreria Ruby è una soluzione professionale per convertire i file XLTM in PDF online. Questo Cloud SDK offre agli sviluppatori Ruby potenti funzionalità e un output PDF perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Ruby utilizzando REST API per convertire XLTM nel formato PDF" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xltm"
            format = 'pdf'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Ruby API per convertire XLTM in PDF" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama celle_cartella di lavoro_Mettere_convertire_metodo della cartella di lavoro per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>rubino 2.5 o più recente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}