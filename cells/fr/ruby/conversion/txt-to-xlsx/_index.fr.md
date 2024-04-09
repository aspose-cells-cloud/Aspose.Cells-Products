---
title:  Convertir TXT en XLSX à l'aide de Ruby
description: Utilisation du SDK Cloud Aspose.Cells pour Ruby pour convertir un fichier au format TXT en fichier au format XLSX.
kwords: Excel, Convert TXT to XLSX, REST, Ruby
howto: How to convert TXT to XLSX using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir TXT en XLSX" h2="Bibliothèque Ruby pour convertir TXT en XLSX" p="Utilisez la conversion API de Cells Cloud pour créer des workflows de feuilles de calcul personnalisés dans les projets Ruby. Il s\'agit d\'une solution professionnelle pour convertir TXT en XLSX et d\'autres formats de documents en ligne à l\'aide de Ruby." urlsection="conversion/txt-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez TXT en XLSX à l\'aide du SDK Cloud Cells pour Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de TXT en XLSX peut être une tâche complexe. Notre SDK Ruby gère toutes les conversions du format TXT vers XLSX tout en préservant le contenu structurel et logique principal de la feuille de calcul TXT source. Notre bibliothèque Ruby fournit une solution professionnelle pour convertir des fichiers TXT en XLSX en ligne. Ce SDK Cloud offre aux développeurs Ruby des fonctionnalités puissantes et garantit une sortie XLSX de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code Ruby pour convertir TXT en XLSX à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.txt"
            format = 'xlsx'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment convertir TXT en XLSX à l\'aide de la bibliothèque Cloud Ruby Cells." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Ruby et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source dans Ruby.</li>
<li>Utilisez la méthode `put_convert_workbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>rubis 2.5 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
