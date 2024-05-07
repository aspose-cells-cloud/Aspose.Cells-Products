---
title:  Convertir JSON en XLS à l'aide de Ruby
description:  Utilisation du SDK Cloud Aspose.Cells pour Ruby pour convertir un fichier au format JSON en fichier au format XLS.
kwords: Excel, Convert JSON to XLS, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert JSON to XLS using the Cells Cloud Ruby library.","description": "How to convert JSON to XLS using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/conversion/json-to-xls/","step": [{ "@type": "HowToStep","name": "How to convert JSON to XLS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/json-to-xls/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert JSON to XLS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/json-to-xls/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert JSON to XLS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/json-to-xls/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to convert JSON to XLS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/json-to-xls/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir JSON en XLS" h2="Bibliothèque Ruby pour convertir JSON en XLS" p="Utilisez la conversion API de Cells Cloud pour créer des workflows de feuilles de calcul personnalisés dans les projets Ruby. Il s\'agit d\'une solution professionnelle pour convertir JSON en XLS et d\'autres formats de documents en ligne à l\'aide de Ruby." urlsection="conversion/json-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez JSON en XLS à l\'aide du SDK Cloud Cells pour Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers JSON vers XLS peut être une tâche complexe. Notre SDK Ruby gère toutes les conversions du format JSON vers XLS tout en préservant le contenu structurel et logique principal de la feuille de calcul JSON source. Notre bibliothèque Ruby fournit une solution professionnelle pour convertir des fichiers JSON en XLS en ligne. Ce SDK Cloud offre aux développeurs Ruby des fonctionnalités puissantes et garantit une sortie XLS de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code Ruby pour convertir JSON en XLS à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.json"
            format = 'xls'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment convertir JSON en XLS à l\'aide de la bibliothèque Cloud Ruby Cells." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Ruby et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source dans Ruby.</li>
<li>Utilisez la méthode `put_convert_workbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>rubis 2.5 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
