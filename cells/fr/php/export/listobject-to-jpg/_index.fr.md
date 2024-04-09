---
title: Exportez LISTOBJECT au format JPG à partir de Excel à l'aide du SDK Cloud Cells pour PHP
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exporter LISTOBJECT vers JPG à partir de Excel" h2="Bibliothèque PHP pour exporter LISTOBJECT vers un fichier JPG" p="Utilisez Export API de Cells Cloud pour exporter les flux de travail d\'objets internes du fichier Excel dans PHP. Il s\'agit d\'une solution professionnelle pour exporter LISTOBJECT au format JPG à partir d\'une feuille de calcul en ligne à l\'aide de PHP." urlsection="export/listobject-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exportez l\'objet LISTOBJECT vers un fichier au format JPG à l\'aide du SDK Cloud Cells pour PHP." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exporter l'objet LISTOBJECT vers un fichier JPG à partir du fichier Excel est une tâche complexe. L'exportation des transitions au format LISTOBJECT au format JPG est effectuée par notre SDK PHP tout en conservant le contenu structurel et logique principal de la feuille de calcul LISTOBJECT source. Notre bibliothèque PHP est une solution professionnelle pour exporter en ligne des objets LISTOBJECT vers des fichiers au format JPG. Ce SDK Cloud offre aux développeurs PHP des fonctionnalités puissantes et une sortie JPG parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Exemple de code dans PHP utilisant REST API pour exporter LISTOBJECT au format JPG à partir d\'une feuille de calcul" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\LightCellsApi;
    $cells = new LightCellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $files = array (
        'DataSource' =>  "C:/datasource.xlsx",
        'AssemblyTest' => "C:/assemblytest.xlsx"
    );
    $result = $cells->postExport( $files,'listobject', 'jpg' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour PHP pour exporter des objets de Excel LISTOBJECT vers JPG" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `postExport` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>PHP 7.4 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
