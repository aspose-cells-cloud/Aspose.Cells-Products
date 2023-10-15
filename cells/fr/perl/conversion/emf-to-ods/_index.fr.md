---
title:  Convertissez EMF en ODS en utilisant Perl
description:  Utilisation du SDK Cloud Aspose.Cells pour Perl pour convertir un fichier au format EMF en fichier au format ODS.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir EMF en ODS" h2="Bibliothèque Perl pour convertir EMF en ODS" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets Perl. Il s\'agit d\'une solution professionnelle pour convertir EMF en ODS et autres formats de documents en ligne à l\'aide de Perl." urlsection="conversion/emf-to-ods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez EMF en ODS à l’aide du SDK Cloud Cells pour Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de EMF en ODS peut être une tâche complexe. Notre SDK Perl gère toutes les conversions du format EMF au format ODS tout en préservant le contenu structurel et logique principal de la feuille de calcul source EMF. Notre bibliothèque Perl fournit une solution professionnelle pour convertir en ligne EMF en fichiers ODS. Ce SDK Cloud offre aux développeurs Perl des fonctionnalités puissantes et garantit une sortie ODS de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl Exemple de code pour convertir EMF en ODS à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "ods";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.emf");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.emf") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.ods") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Perl pour convertir EMF en ODS" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `put_convert_workbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
