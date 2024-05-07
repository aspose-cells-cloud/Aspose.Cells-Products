---
title:  Enregistrez XLT sous XLTX en utilisant Perl
description:  Utilisation du SDK Cloud Aspose.Cells pour Perl pour enregistrer le fichier au format XLT en tant que fichier au format XLTX.
kwords: Excel, Save XLT as XLTX, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLT as XLTX using the Cells Cloud Perl library.","description": "How to save XLT as XLTX using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/saveas/xlt-to-xltx/","step": [{ "@type": "HowToStep","name": "How to save XLT as XLTX using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xlt-to-xltx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLT as XLTX using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xlt-to-xltx/","text": "Install Perl library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLT as XLTX using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xlt-to-xltx/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to save XLT as XLTX using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xlt-to-xltx/","text": "Call post_workbook_save_as method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer XLT sous XLTX" h2="Bibliothèque Perl pour enregistrer XLT au format XLTX" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Perl. Il s\'agit d\'une solution professionnelle pour enregistrer XLT au format XLTX et d\'autres formats de documents en ligne à l\'aide de Perl." urlsection="saveas/xlt-to-xltx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrez un fichier XLT sous XLTX dans Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de XLT au format XLTX est une tâche complexe. Toutes les transitions du format XLT vers XLTX sont effectuées par notre SDK Perl tout en conservant le contenu structurel et logique principal de la feuille de calcul XLT source. Notre bibliothèque Perl est une solution professionnelle pour enregistrer XLT sous forme de fichiers XLTX en ligne. Ce SDK Cloud offre aux développeurs Perl des fonctionnalités puissantes et une sortie XLTX parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Exemple de code pour enregistrer XLT au format XLTX à l\'aide de REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.xlt';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.xltx';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment enregistrer XLT au format XLTX à l\'aide de la bibliothèque Cells Cloud Perl." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Perl et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Perl.</li>
<li>Poste d'appel_classeur_méthode save_as pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
