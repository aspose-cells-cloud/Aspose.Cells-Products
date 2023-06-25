---
title:  Esporta LISTOBJECT in XPS dal foglio di calcolo utilizzando Ruby API
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
url: /it/ruby/export/listobject-to-xps/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API per esportare LISTOBJECT nel file XPS" h2="Libreria Ruby per esportare LISTOBJECT nel file XPS" p="Usa Cells Esporta REST API per esportare i flussi di lavoro degli oggetti interni del foglio di calcolo in Ruby. Questa è una soluzione professionale per esportare LISTOBJECT nel file in formato XPS dal foglio di calcolo online utilizzando Ruby." urlsection="export/listobject-to-xps/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Esporta l\'oggetto LISTOBJECT nel file di formato XPS in Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto LISTOBJECT nel file XPS dal foglio di calcolo è un'attività complessa. L'esportazione delle transizioni di formato da LISTOBJECT a XPS viene eseguita dal nostro SDK Ruby mantenendo il contenuto strutturale e logico principale del foglio di calcolo LISTOBJECT di origine. La nostra libreria Ruby è una soluzione professionale per esportare oggetti LISTOBJECT in file in formato XPS online. Questo Cloud SDK offre agli sviluppatori Ruby potenti funzionalità e un output XPS perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Ruby utilizzando REST API per esportare LISTOBJECT nel formato XPS dal foglio di calcolo" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::LiteCellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            files = {}      
            name = $DataSourceXlsx
            files[name] = ::File.open(File.expand_path("data/"+name),"r") 
            name =$AssemblyTestXlsx 
            files[name] = ::File.open(File.expand_path("data/"+name),"r")
            format = 'xps'
            objectType =  'listobject'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Ruby API per esportare LISTOBJECT in XPS" >}}
<li> Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione</li>
<li>Inizializza CellsApi con ID client, segreto client, URL di base e versione API</li>
<li>Chiama il metodo post_export per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>rubino 2.5 o più recente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
