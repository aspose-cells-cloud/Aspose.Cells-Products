---
title:  Exporter la FEUILLE DE TRAVAIL au format CSV à partir de Excel à l'aide du SDK Cloud Cells pour Ruby
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exporter la FEUILLE DE TRAVAIL au format CSV à partir du Excel" h2="Bibliothèque Ruby pour exporter WORKSHEET vers un fichier CSV" p="Utilisez Export API de Cells Cloud pour exporter les workflows d\'objets internes du fichier Excel dans Ruby. Il s\'agit d\'une solution professionnelle pour exporter WORKSHEET vers un fichier au format CSV à partir d\'une feuille de calcul en ligne à l\'aide de Ruby." urlsection="export/worksheet-to-csv/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporter l\'objet WORKSHEET vers un fichier au format CSV à l\'aide du SDK Cloud Cells pour Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter l'objet WORKSHEET vers un fichier CSV à partir du fichier Excel est une tâche complexe. Les transitions d'exportation de WORKSHEET au format CSV sont effectuées par notre SDK Ruby tout en conservant le contenu structurel et logique principal de la feuille de calcul WORKSHEET source. Notre bibliothèque Ruby est une solution professionnelle pour exporter des objets WORKSHEET vers des fichiers au format CSV en ligne. Ce SDK Cloud offre aux développeurs Ruby des fonctionnalités puissantes et une sortie CSV parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code dans Ruby utilisant REST API pour exporter WORKSHEET au format CSV à partir d\'une feuille de calcul" gistPath="" %}}
  
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
            format = 'csv'
            objectType =  'worksheet'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Ruby pour exporter des objets de Excel WORKSHEET vers CSV" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Appelez la méthode post_export pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>rubis 2.5 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
