---
title:  Exportez la FEUILLE DE TRAVAIL vers WMF à partir de Excel à l'aide du SDK Cloud Cells pour Perl.
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exporter la FEUILLE DE TRAVAIL vers WMF à partir du Excel" h2="Bibliothèque Perl pour exporter WORKSHEET vers un fichier WMF" p="Utilisez Export API de Cells Cloud pour exporter les flux de travail d\'objets internes du fichier Excel dans Perl. Il s\'agit d\'une solution professionnelle pour exporter une FEUILLE DE TRAVAIL au format WMF à partir d\'une feuille de calcul en ligne à l\'aide de Perl." urlsection="export/worksheet-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportez l\'objet WORKSHEET vers un fichier au format WMF à l\'aide du SDK Cloud Cells pour Perl." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter l'objet WORKSHEET vers le fichier WMF à partir du fichier Excel est une tâche complexe. Les transitions d'exportation de WORKSHEET au format WMF sont effectuées par notre SDK Perl tout en conservant le contenu structurel et logique principal de la feuille de calcul WORKSHEET source. Notre bibliothèque Perl est une solution professionnelle pour exporter en ligne des objets WORKSHEET vers des fichiers au format WMF. Ce SDK Cloud offre aux développeurs Perl des fonctionnalités puissantes et une sortie WMF parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code dans Perl utilisant REST API pour exporter WORKSHEET au format WMF à partir d\'une feuille de calcul" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use MIME::Base64;
    use AsposeCellsCloud::LightCellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::LightCellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $filemap = { 'Book1.xlsx' => '~/TestData/Book1.xlsx', 'myDocument.xlsx' => ~/TestData/myDocument.xlsx'};
    my $result = $instance->post_export(file => $filemap , object_type => 'worksheet',format => 'wmf');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Perl pour exporter des objets de Excel WORKSHEET vers WMF" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Appelez la méthode post_export pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
