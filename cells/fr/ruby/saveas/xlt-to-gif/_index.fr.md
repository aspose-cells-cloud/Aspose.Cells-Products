---
title:  Enregistrer XLT au format GIF en utilisant Ruby
description:  Utilisation du SDK Cloud Aspose.Cells pour Ruby pour enregistrer le fichier au format XLT au format GIF.
kwords: Excel, Save XLT as GIF, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLT as GIF using the Cells Cloud Ruby library.","description": "How to save XLT as GIF using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/saveas/xlt-to-gif/","step": [{ "@type": "HowToStep","name": "How to save XLT as GIF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlt-to-gif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLT as GIF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlt-to-gif/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLT as GIF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlt-to-gif/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to save XLT as GIF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlt-to-gif/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer XLT au format GIF" h2="Bibliothèque Ruby pour enregistrer XLT au format GIF" p="Utilisez SaveAs API sur Cells Cloud pour créer des workflows de feuilles de calcul personnalisés dans Ruby. Il s\'agit d\'une solution professionnelle pour enregistrer XLT au format GIF et autres formats de documents en ligne à l\'aide de Ruby." urlsection="saveas/xlt-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrer un fichier XLT au format GIF dans Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement des formats de fichiers XLT au format GIF est une tâche complexe. Toutes les transitions du format XLT vers GIF sont effectuées par notre SDK Ruby tout en conservant le contenu structurel et logique principal de la feuille de calcul XLT source. Notre bibliothèque Ruby est une solution professionnelle pour enregistrer XLT sous forme de fichiers GIF en ligne. Ce SDK Cloud offre aux développeurs Ruby des fonctionnalités puissantes et une sortie GIF parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code Ruby pour enregistrer XLT au format GIF à l\'aide de REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.xlt'
    save_options = nil
    newfilename = 'Book1Saveas.gif'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment enregistrer XLT au format GIF à l\'aide de la bibliothèque Cloud Ruby Cells." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Ruby et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source dans Ruby.</li>
<li>Utilisez la méthode `post_workbook_save_as` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>rubis 2.5 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
