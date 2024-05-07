---
title:  Exportez SHAPE vers TIFF à partir de Excel à l'aide du SDK Cloud Cells pour Ruby
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
kwords: Excel, shape, tiff, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel SHAPE to TIFF","description": "How to use Cells Cloud SDK for Ruby to export objects from Excel SHAPE to TIFF","image": {"@type": "ImageObject"},"url": "/ruby/export/shape-to-tiff/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel SHAPE to TIFF step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/shape-to-tiff/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel SHAPE to TIFF step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/shape-to-tiff/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel SHAPE to TIFF step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/shape-to-tiff/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exporter SHAPE vers TIFF à partir de Excel" h2="Bibliothèque Ruby pour exporter SHAPE vers le fichier TIFF" p="Utilisez Export API de Cells Cloud pour exporter les workflows d\'objets internes du fichier Excel dans Ruby. Il s\'agit d\'une solution professionnelle pour exporter SHAPE au format TIFF à partir d\'une feuille de calcul en ligne à l\'aide de Ruby." urlsection="export/shape-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporter l\'objet SHAPE vers un fichier au format TIFF à l\'aide du SDK Cloud Cells pour Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter l'objet SHAPE vers le fichier TIFF à partir du fichier Excel est une tâche complexe. L'exportation des transitions au format SHAPE vers TIFF est effectuée par notre SDK Ruby tout en conservant le contenu structurel et logique principal de la feuille de calcul SHAPE source. Notre bibliothèque Ruby est une solution professionnelle pour exporter des objets SHAPE au format TIFF en ligne. Ce SDK Cloud offre aux développeurs Ruby des fonctionnalités puissantes et une sortie TIFF parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code dans Ruby utilisant REST API pour exporter SHAPE au format TIFF à partir d\'une feuille de calcul" gistPath="" %}}
  
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
            format = 'tiff'
            objectType =  'shape'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Ruby pour exporter des objets de Excel SHAPE vers TIFF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Appelez la méthode post_export pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>rubis 2.5 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
