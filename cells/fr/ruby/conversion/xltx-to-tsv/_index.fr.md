﻿---
title:  Convertir XLTX en TSV API pour Ruby
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/ruby/conversion/xltx-to-tsv/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API pour convertir XLTX en TSV" h2="Bibliothèque Ruby pour convertir XLTX en TSV" p="Utilisez Cells Conversion REST API pour créer des workflows de feuille de calcul personnalisés dans Ruby. Il s\'agit d\'une solution professionnelle pour convertir XLTX en TSV et d\'autres formats de documents en ligne à l\'aide de Ruby." urlsection="conversion/xltx-to-tsv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier XLTX en TSV en Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de XLTX en TSV est une tâche complexe. Toutes les transitions de format XLTX vers TSV sont effectuées par notre SDK Ruby tout en conservant le contenu structurel et logique principal de la feuille de calcul XLTX source. Notre bibliothèque Ruby est une solution professionnelle pour convertir en ligne des fichiers XLTX en TSV. Ce SDK Cloud offre aux développeurs Ruby des fonctionnalités puissantes et une sortie TSV parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Ruby utilisant REST API pour convertir XLTX au format TSV" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xltx"
            format = 'tsv'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Ruby API pour convertir XLTX en TSV" >}}
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