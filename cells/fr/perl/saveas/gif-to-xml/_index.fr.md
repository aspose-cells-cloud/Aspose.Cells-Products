﻿---
title:  Enregistrer le GIF au format XML API pour Perl
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/perl/saveas/gif-to-xml/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API pour enregistrer le GIF au format XML" h2="Perl bibliothèque pour enregistrer GIF en XML" p="Utilisez Cells SaveAs REST API pour créer des flux de travail de feuille de calcul personnalisés dans Perl. Il s\'agit d\'une solution professionnelle pour enregistrer en ligne GIF au format XML et d\'autres formats de document à l\'aide de Perl." urlsection="saveas/gif-to-xml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrer un fichier GIF au format XML au Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement de formats de fichiers GIF en XML est une tâche complexe. Toutes les transitions de format GIF vers XML sont effectuées par notre SDK Perl tout en conservant le contenu structurel et logique principal de la feuille de calcul GIF source. Notre bibliothèque Perl est une solution professionnelle pour enregistrer en ligne des fichiers GIF au format XML. Ce SDK Cloud offre aux développeurs Perl des fonctionnalités puissantes et une sortie XML parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Perl utilisant REST API pour enregistrer GIF au format XML" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.gif';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.xml';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Perl API pour enregistrer GIF au format XML" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Cellules d'appel_sauvegarder_comme_poste_document_sauvegarder_comme méthode pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}