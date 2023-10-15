---
title:  Convertir des NUMBERS en GIF à l'aide de Ruby
description:  Utilisation du SDK Cloud Aspose.Cells pour Ruby pour convertir un fichier au format NUMBERS en fichier au format GIF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir des NUMÉROS en GIF" h2="Bibliothèque Ruby pour convertir des NUMBERS en GIF" p="Utilisez la conversion API de Cells Cloud pour créer des workflows de feuilles de calcul personnalisés dans les projets Ruby. Il s\'agit d\'une solution professionnelle pour convertir des NUMBERS en GIF et d\'autres formats de documents en ligne à l\'aide de Ruby." urlsection="conversion/numbers-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez des NUMBERS en GIF à l\'aide du SDK Cloud Cells pour Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers NUMBERS en GIF peut être une tâche complexe. Notre SDK Ruby gère toutes les conversions du format NUMBERS au format GIF tout en préservant le contenu structurel et logique principal de la feuille de calcul NUMBERS source. Notre bibliothèque Ruby fournit une solution professionnelle pour convertir des NUMBERS en fichiers GIF en ligne. Ce SDK Cloud offre aux développeurs Ruby des fonctionnalités puissantes et garantit une sortie GIF de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code Ruby pour convertir des NUMBERS en GIF à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.numbers"
            format = 'gif'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Ruby pour convertir des fichiers Excel vers d\'autres formats NUMBERS en GIF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `put_convert_workbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>rubis 2.5 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
