﻿---
title:  Enregistrez PNG sous PDF en utilisant Perl
description:  Utilisation du SDK Cloud Aspose.Cells pour Perl pour enregistrer le fichier au format PNG en tant que fichier au format PDF.
kwords: Excel, Save PNG as PDF, REST, Perl
howto: How to save PNG as PDF using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer le PNG sous le nom PDF" h2="Bibliothèque Perl pour enregistrer PNG sous le nom PDF" p="Utilisez SaveAs API de Cells Cloud pour créer des flux de travail de feuille de calcul personnalisés dans Perl. Il s\'agit d\'une solution professionnelle pour enregistrer PNG sous PDF et d\'autres formats de documents en ligne à l\'aide de Perl." urlsection="saveas/png-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrer un fichier PNG sous PDF dans Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de PNG à PDF est une tâche complexe. Toutes les transitions de format PNG à PDF sont effectuées par notre SDK Perl tout en conservant le contenu structurel et logique principal de la feuille de calcul source PNG. Notre bibliothèque Perl est une solution professionnelle pour enregistrer PNG en tant que fichiers PDF en ligne. Ce SDK Cloud offre aux développeurs Perl des fonctionnalités puissantes et une sortie PDF parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Exemple de code pour enregistrer PNG sous PDF en utilisant REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.png';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.pdf';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment enregistrer PNG sous PDF à l\'aide de la bibliothèque Cells Cloud Perl." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque Perl et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Perl.</li>
<li>Poste d'appel_classeur_méthode save_as pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
