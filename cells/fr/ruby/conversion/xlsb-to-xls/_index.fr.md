---
title:  Convertir XLSB en XLS en utilisant Ruby
description: Utilisation du SDK Cloud Aspose.Cells pour Ruby pour convertir un fichier au format XLSB en fichier au format XLS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir XLSB en XLS" h2="Bibliothèque Ruby pour convertir XLSB en XLS" p="Utilisez la conversion API de Cells Cloud pour créer des workflows de feuilles de calcul personnalisés dans les projets Ruby. Il s\'agit d\'une solution professionnelle pour convertir XLSB en XLS et d\'autres formats de documents en ligne à l\'aide de Ruby." urlsection="conversion/xlsb-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez XLSB en XLS à l\'aide du SDK Cloud Cells pour Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers XLSB en XLS peut être une tâche complexe. Notre SDK Ruby gère toutes les conversions du format XLSB vers XLS tout en préservant le contenu structurel et logique principal de la feuille de calcul XLSB source. Notre bibliothèque Ruby fournit une solution professionnelle pour convertir des fichiers XLSB en XLS en ligne. Ce SDK Cloud offre aux développeurs Ruby des fonctionnalités puissantes et garantit une sortie XLS de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code Ruby pour convertir XLSB en XLS à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xlsb"
            format = 'xls'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Ruby pour convertir des fichiers Excel vers d\'autres formats XLSB en XLS" >}}
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
