﻿---
title: Exporter WORKBOOK vers XPS à partir d'une feuille de calcul à l'aide de Ruby API
description: Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers Excel et d'objets internes vers des types de fichiers de format. SDK prend en charge les types de langages de développement. Ils incluent Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby et Swift.
url: /fr/ruby/export/workbook-to-xps/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API pour exporter WORKBOOK vers le fichier XPS" h2="Bibliothèque Ruby pour exporter WORKBOOK vers le fichier XPS" p="Utilisez Cells Export REST API pour exporter les workflows d\'objets internes de feuille de calcul dans Ruby. Il s\'agit d\'une solution professionnelle pour exporter WORKBOOK vers un fichier au format XPS à partir d\'une feuille de calcul en ligne à l\'aide de Ruby." urlsection="export/workbook-to-xps/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exporter l\'objet WORKBOOK vers un fichier au format XPS dans Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter l'objet WORKBOOK vers le fichier XPS à partir d'une feuille de calcul est une tâche complexe. L'exportation des transitions de format WORKBOOK vers XPS est effectuée par notre SDK Ruby tout en conservant le contenu structurel et logique principal de la feuille de calcul WORKBOOK source. Notre bibliothèque Ruby est une solution professionnelle pour exporter en ligne des objets WORKBOOK vers des fichiers au format XPS. Ce SDK Cloud offre aux développeurs Ruby des fonctionnalités puissantes et une sortie XPS parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Ruby utilisant REST API pour exporter WORKBOOK au format XPS à partir d\'une feuille de calcul" gistPath="" %}}
  
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
            objectType =  'workbook'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Ruby API pour exporter WORKBOOK vers XPS" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode post_export pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>ruby 2.5 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}