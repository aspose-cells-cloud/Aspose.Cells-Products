---
title:  Esporta FOGLIO DI LAVORO in SQL da Excel utilizzando Cells Cloud SDK per Ruby
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Esporta FOGLIO DI LAVORO in SQL da Excel" h2="Libreria Ruby per esportare FOGLIO DI LAVORO in file SQL" p="Utilizzare Esporta API di Cells Cloud per esportare i flussi di lavoro degli oggetti interni del file Excel in Ruby. Questa è una soluzione professionale per esportare FOGLIO DI LAVORO in file in formato SQL da un foglio di calcolo online utilizzando Ruby." urlsection="export/worksheet-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Esporta l\'oggetto WORKSHEET in un file in formato SQL utilizzando Cells Cloud SDK per Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto FOGLIO DI LAVORO in un file SQL dal file Excel è un'attività complessa. L'esportazione di FOGLIO DI LAVORO in transizioni in formato SQL viene eseguita dal nostro Ruby SDK mantenendo il contenuto strutturale e logico principale del foglio di calcolo di FOGLIO DI LAVORO di origine. La nostra libreria Ruby è una soluzione professionale per esportare oggetti WORKSHEET in file in formato SQL online. Questo Cloud SDK offre agli sviluppatori Ruby funzionalità potenti e output SQL perfetto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Esempio di codice in Ruby utilizzando REST API per esportare FOGLIO DI LAVORO in formato SQL dal foglio di calcolo" gistPath="" %}}
  
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
            format = 'sql'
            objectType =  'worksheet'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK for Ruby per esportare oggetti da Excel WORKSHEET a SQL" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Chiama il metodo post_export per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>rubino 2.5 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
