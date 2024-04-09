---
title:  Convertissez GIF en TSV en utilisant Perl
description:  Utilisation du SDK Cloud Aspose.Cells pour Perl pour convertir un fichier au format GIF en fichier au format TSV.
kwords: Excel, Convert GIF to TSV, REST, Perl
howto: How to convert GIF to TSV using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir GIF en TSV" h2="Bibliothèque Perl pour convertir GIF en TSV" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets Perl. Il s\'agit d\'une solution professionnelle pour convertir des GIF en TSV et d\'autres formats de documents en ligne à l\'aide du Perl." urlsection="conversion/gif-to-tsv/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez GIF en TSV à l\'aide du SDK Cloud Cells pour Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers GIF en TSV peut être une tâche complexe. Notre SDK Perl gère toutes les conversions du format GIF au format TSV tout en préservant le contenu structurel et logique principal de la feuille de calcul GIF source. Notre bibliothèque Perl fournit une solution professionnelle pour convertir des fichiers GIF en fichiers TSV en ligne. Ce SDK Cloud offre aux développeurs Perl des fonctionnalités puissantes et garantit une sortie TSV de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Exemple de code pour convertir GIF en TSV à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "tsv";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.gif");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.gif") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.tsv") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment convertir GIF en TSV à l\'aide de la bibliothèque Cells Cloud Perl." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez le package Perl et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Perl.</li>
<li>Utilisez la méthode `put_convert_workbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
