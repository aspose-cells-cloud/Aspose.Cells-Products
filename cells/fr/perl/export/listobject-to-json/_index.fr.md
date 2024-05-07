---
title:  Exportez LISTOBJECT vers JSON à partir de Excel à l'aide du SDK Cloud Cells pour Perl
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
kwords: Excel, listobject, json, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to JSON","description": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to JSON","image": {"@type": "ImageObject"},"url": "/perl/export/listobject-to-json/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to JSON step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/listobject-to-json/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to JSON step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/listobject-to-json/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel LISTOBJECT to JSON step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/listobject-to-json/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exporter LISTOBJECT vers JSON à partir de Excel" h2="Bibliothèque Perl pour exporter LISTOBJECT vers un fichier JSON" p="Utilisez Export API de Cells Cloud pour exporter les flux de travail d\'objets internes du fichier Excel dans Perl. Il s\'agit d\'une solution professionnelle pour exporter LISTOBJECT vers un fichier au format JSON à partir d\'une feuille de calcul en ligne à l\'aide de Perl." urlsection="export/listobject-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportez l\'objet LISTOBJECT vers un fichier au format JSON à l\'aide du SDK Cloud Cells pour Perl." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter l'objet LISTOBJECT vers le fichier JSON à partir du fichier Excel est une tâche complexe. L'exportation des transitions au format LISTOBJECT vers JSON est effectuée par notre SDK Perl tout en conservant le contenu structurel et logique principal de la feuille de calcul LISTOBJECT source. Notre bibliothèque Perl est une solution professionnelle pour exporter des objets LISTOBJECT vers des fichiers au format JSON en ligne. Ce SDK Cloud offre aux développeurs Perl des fonctionnalités puissantes et une sortie JSON parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code dans Perl utilisant REST API pour exporter LISTOBJECT au format JSON à partir d\'une feuille de calcul" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'listobject',format => 'json');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour Perl pour exporter des objets de Excel LISTOBJECT vers JSON" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Appelez la méthode post_export pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
