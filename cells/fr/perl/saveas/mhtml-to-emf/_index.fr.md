---
title:  Enregistrez MHTML sous EMF en utilisant Perl
description:  Utilisation du SDK Cloud Aspose.Cells pour Perl pour enregistrer le fichier au format MHTML au format EMF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Enregistrer MHTML sous EMF" h2="Bibliothèque Perl pour enregistrer MHTML sous EMF" p="Utilisez SaveAs API de Cells Cloud pour créer des flux de travail de feuille de calcul personnalisés dans Perl. Il s\'agit d\'une solution professionnelle pour enregistrer MHTML sous EMF et d\'autres formats de documents en ligne à l\'aide de Perl." urlsection="saveas/mhtml-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier MHTML sous EMF dans Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers MHTML sous le nom EMF est une tâche complexe. Toutes les transitions du format MHTML vers EMF sont effectuées par notre SDK Perl tout en conservant le contenu structurel et logique principal de la feuille de calcul MHTML source. Notre bibliothèque Perl est une solution professionnelle pour enregistrer du MHTML sous forme de fichiers EMF en ligne. Ce SDK Cloud offre aux développeurs Perl des fonctionnalités puissantes et une sortie EMF parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl Exemple de code pour enregistrer MHTML sous EMF à l\'aide de REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.mhtml';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.emf';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Perl pour enregistrer les fichiers Excel sous d\'autres formats MHTML sous le nom EMF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Poste d'appel_classeur_méthode save_as pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
