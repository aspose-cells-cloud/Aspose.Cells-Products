---
title: Convertir XLSB en XML API pour Perl
description:  Utilisation du SDK Cloud Aspose.Cells pour Perl pour convertir le fichier au format XLSB en fichier au format XML.
url: /fr/perl/conversion/xlsb-to-xml/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API pour convertir XLSB en XML" h2="bibliothèque Perl pour convertir XLSB en XML" p="Utilisez Cells Conversion REST API pour créer des workflows de feuille de calcul personnalisés dans Perl. Il s\'agit d\'une solution professionnelle pour convertir XLSB en XML et d\'autres formats de documents en ligne à l\'aide de Perl." urlsection="conversion/xlsb-to-xml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertir un fichier XLSB en XML en Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion de formats de fichiers XLSB en XML est une tâche complexe. Toutes les transitions de format XLSB vers XML sont effectuées par notre SDK Perl tout en conservant le contenu structurel et logique principal de la feuille de calcul XLSB source. Notre bibliothèque Perl est une solution professionnelle pour convertir en ligne des fichiers XLSB en XML. Ce SDK Cloud offre aux développeurs Perl des fonctionnalités puissantes et une sortie XML parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans Perl utilisant REST API pour convertir XLSB au format XML" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xml";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xlsb");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xlsb") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xml") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser Perl API pour convertir XLSB en XML" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Cellules d'appel_classeur_mettre_convertir_méthode de classeur pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
