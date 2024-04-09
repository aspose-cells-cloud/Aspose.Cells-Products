---
title:  Enregistrez ODS au format GIF en utilisant Perl
description: Utilisation du SDK Cloud Aspose.Cells pour Perl pour enregistrer le fichier au format ODS au format GIF.
kwords: Excel, Save ODS as GIF, REST, Perl
howto: How to save ODS as GIF using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer l\'ODS au format GIF" h2="Bibliothèque Perl pour enregistrer l\'ODS au format GIF" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans Perl. Il s\'agit d\'une solution professionnelle pour enregistrer l\'ODS au format GIF et d\'autres formats de document en ligne à l\'aide de Perl." urlsection="saveas/ods-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrer un fichier ODS au format GIF dans Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement des formats de fichiers d'ODS au format GIF est une tâche complexe. Toutes les transitions du format ODS vers GIF sont effectuées par notre SDK Perl tout en conservant le contenu structurel et logique principal de la feuille de calcul ODS source. Notre bibliothèque Perl est une solution professionnelle pour enregistrer des ODS sous forme de fichiers GIF en ligne. Ce SDK Cloud offre aux développeurs Perl des fonctionnalités puissantes et une sortie GIF parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Exemple de code pour enregistrer ODS au format GIF à l\'aide de REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.ods';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.gif';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment enregistrer ODS au format GIF à l\'aide de la bibliothèque Cells Cloud Perl." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Perl et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Perl.</li>
<li>Poste d'appel_classeur_méthode save_as pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
