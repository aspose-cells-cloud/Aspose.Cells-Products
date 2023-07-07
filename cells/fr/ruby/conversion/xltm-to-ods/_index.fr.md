---
title:  Convertir XLTM en ODS API pour Ruby
description:  Utilisation du SDK Cloud Aspose.Cells pour Ruby pour convertir le fichier au format XLTM en fichier au format ODS.
url: /fr/ruby/conversion/xltm-to-ods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API pour convertir XLTM en ODS" h2="Bibliothèque Ruby pour convertir XLTM en ODS" p="Utilisez Cells Conversion REST API pour créer des workflows de feuille de calcul personnalisés dans Ruby. Il s\'agit d\'une solution professionnelle pour convertir XLTM en ODS et d\'autres formats de documents en ligne à l\'aide de Ruby." urlsection="conversion/xltm-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier XLTM en ODS en Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de XLTM en ODS est une tâche complexe. Toutes les transitions de format XLTM vers ODS sont effectuées par notre SDK Ruby tout en conservant le contenu structurel et logique principal de la feuille de calcul source XLTM. Notre bibliothèque Ruby est une solution professionnelle pour convertir en ligne des fichiers XLTM en ODS. Ce SDK Cloud offre aux développeurs Ruby des fonctionnalités puissantes et une sortie ODS parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code en Ruby utilisant REST API pour convertir XLTM au format ODS" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xltm"
            format = 'ods'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Ruby API pour convertir XLTM en ODS" >}}
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
