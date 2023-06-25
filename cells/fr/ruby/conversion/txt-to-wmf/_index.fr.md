---
title:  Convertir TXT en WMF API pour Ruby
description:  Utilisation du SDK Cloud Aspose.Cells pour Ruby pour convertir le fichier au format TXT en fichier au format WMF.
url: /fr/ruby/conversion/txt-to-wmf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API pour convertir TXT en WMF" h2="bibliothèque Ruby pour convertir TXT en WMF" p="Utilisez Cells Conversion REST API pour créer des workflows de feuille de calcul personnalisés dans Ruby. Il s\'agit d\'une solution professionnelle pour convertir TXT en WMF et d\'autres formats de documents en ligne à l\'aide de Ruby." urlsection="conversion/txt-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier TXT en WMF en Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de TXT en WMF est une tâche complexe. Toutes les transitions de format TXT vers WMF sont effectuées par notre SDK Ruby tout en conservant le contenu structurel et logique principal de la feuille de calcul TXT source. Notre bibliothèque Ruby est une solution professionnelle pour convertir des fichiers TXT en WMF en ligne. Ce SDK Cloud offre aux développeurs Ruby des fonctionnalités puissantes et une sortie WMF parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Ruby utilisant REST API pour convertir le format TXT au format WMF" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.txt"
            format = 'wmf'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Ruby API pour convertir TXT en WMF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Cellules d'appel_classeur_mettre_convertir_méthode de classeur pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>ruby 2.5 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
