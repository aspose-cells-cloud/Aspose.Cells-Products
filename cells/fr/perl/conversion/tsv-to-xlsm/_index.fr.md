---
title:  Convertissez TSV en XLSM en utilisant Perl
description:  Utilisation du SDK Cloud Aspose.Cells pour Perl pour convertir un fichier au format TSV en fichier au format XLSM.
kwords: Excel, Convert TSV to XLSM, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert TSV to XLSM using the Cells Cloud Perl library.","description": "How to convert TSV to XLSM using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/conversion/tsv-to-xlsm/","step": [{ "@type": "HowToStep","name": "How to convert TSV to XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/tsv-to-xlsm/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert TSV to XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/tsv-to-xlsm/","text": "Install Perl package and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert TSV to XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/tsv-to-xlsm/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to convert TSV to XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/conversion/tsv-to-xlsm/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir TSV en XLSM" h2="Bibliothèque Perl pour convertir TSV en XLSM" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets Perl. Il s\'agit d\'une solution professionnelle pour convertir TSV en XLSM et d\'autres formats de documents en ligne en utilisant le Perl." urlsection="conversion/tsv-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convertissez TSV en XLSM à l\'aide du SDK Cloud Cells pour Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers TSV en XLSM peut être une tâche complexe. Notre SDK Perl gère toutes les conversions du format TSV vers XLSM tout en préservant le contenu structurel et logique principal de la feuille de calcul TSV source. Notre bibliothèque Perl fournit une solution professionnelle pour convertir des fichiers TSV en XLSM en ligne. Ce SDK Cloud offre aux développeurs Perl des fonctionnalités puissantes et garantit une sortie XLSM de haute qualité.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Exemple de code pour convertir TSV en XLSM à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xlsm";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.tsv");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.tsv") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xlsm") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment convertir TSV en XLSM à l\'aide de la bibliothèque Cells Cloud Perl." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez le package Perl et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en Perl.</li>
<li>Utilisez la méthode `put_convert_workbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
