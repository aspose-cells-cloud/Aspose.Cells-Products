---
title:  Esporta LISTOBJECT in PDF da Excel utilizzando Cells Cloud SDK per Ruby
description:  Aspose.Cells Cloud REST API supporta l'esportazione di file in formato {0} in {1} utilizzando {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Esporta LISTOBJECT a PDF da Excel" h2="Libreria Ruby per esportare LISTOBJECT nel file PDF" p="Utilizzare Esporta API di Cells Cloud per esportare i flussi di lavoro degli oggetti interni del file Excel in Ruby. Questa è una soluzione professionale per esportare LISTOBJECT nel file in formato PDF da un foglio di calcolo online utilizzando Ruby." urlsection="export/listobject-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Esporta l\'oggetto LISTOBJECT nel file in formato PDF utilizzando Cells Cloud SDK per Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Esportare l'oggetto LISTOBJECT nel file PDF dal file Excel è un'attività complessa. L'esportazione di LISTOBJECT nelle transizioni di formato PDF viene eseguita dal nostro Ruby SDK mantenendo il contenuto strutturale e logico principale del foglio di calcolo LISTOBJECT di origine. La nostra libreria Ruby è una soluzione professionale per esportare online oggetti LISTOBJECT in file in formato PDF. Questo Cloud SDK offre agli sviluppatori Ruby funzionalità potenti e un output PDF perfetto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Esempio di codice in Ruby utilizzando REST API per esportare LISTOBJECT nel formato PDF dal foglio di calcolo" gistPath="" %}}
  
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
            format = 'pdf'
            objectType =  'listobject'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Come utilizzare Cells Cloud SDK per Ruby per esportare oggetti da Excel LISTOBJECT a PDF" >}}
<li> Registra un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione</li>
<li>Inizializza Cells API con l'ID cliente, il segreto cliente, l'URL di base e la versione API.</li>
<li>Chiama il metodo post_export per ottenere il flusso risultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisiti di sistema" >}}
<li>rubino 2.5 o successivo</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
