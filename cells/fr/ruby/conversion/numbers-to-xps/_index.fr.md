---
title:  Convertir des NOMBRES en XPS en utilisant Ruby
description:  Utilisation du SDK Cloud Aspose.Cells pour Ruby pour convertir un fichier au format NUMBERS en fichier au format XPS.
kwords: Excel, Convert NUMBERS to XPS, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert NUMBERS to XPS using the Cells Cloud Ruby library.","description": "How to convert NUMBERS to XPS using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/conversion/numbers-to-xps/","step": [{ "@type": "HowToStep","name": "How to convert NUMBERS to XPS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/numbers-to-xps/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert NUMBERS to XPS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/numbers-to-xps/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert NUMBERS to XPS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/numbers-to-xps/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to convert NUMBERS to XPS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/numbers-to-xps/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir des NOMBRES en XPS" h2="Bibliothèque Ruby pour convertir des NUMBERS en XPS" p="Utilisez la conversion API de Cells Cloud pour créer des workflows de feuilles de calcul personnalisés dans les projets Ruby. Il s\'agit d\'une solution professionnelle pour convertir des NUMÉROS en XPS et d\'autres formats de documents en ligne à l\'aide de Ruby." urlsection="conversion/numbers-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez NUMBERS en XPS à l\'aide du SDK Cloud Cells pour Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de NUMBERS en XPS peut être une tâche complexe. Notre SDK Ruby gère toutes les conversions du format NUMBERS vers XPS tout en préservant le contenu structurel et logique principal de la feuille de calcul NUMBERS source. Notre bibliothèque Ruby fournit une solution professionnelle pour convertir en ligne des fichiers NUMBERS en XPS. Ce SDK Cloud offre aux développeurs Ruby des fonctionnalités puissantes et garantit une sortie XPS de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code Ruby pour convertir NUMBERS en XPS à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.numbers"
            format = 'xps'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment convertir NUMBERS en XPS à l\'aide de la bibliothèque Cloud Ruby Cells." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Ruby et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source dans Ruby.</li>
<li>Utilisez la méthode `put_convert_workbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>rubis 2.5 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
