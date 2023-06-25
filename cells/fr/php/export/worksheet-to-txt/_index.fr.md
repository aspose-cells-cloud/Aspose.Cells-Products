---
title: Exporter WORKSHEET vers TXT à partir d'une feuille de calcul en utilisant PHP API
description:  Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers au format {0} vers {1} à l'aide de {2}.
url: /fr/php/export/worksheet-to-txt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API pour exporter la FEUILLE DE TRAVAIL vers un fichier TXT" h2="PHP bibliothèque pour exporter WORKSHEET vers un fichier TXT" p="Utilisez Cells Export REST API pour exporter les workflows d\'objets internes de la feuille de calcul dans PHP. Il s\'agit d\'une solution professionnelle pour exporter WORKSHEET vers un fichier au format TXT à partir d\'une feuille de calcul en ligne à l\'aide de PHP." urlsection="export/worksheet-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exporter l\'objet WORKSHEET vers un fichier au format TXT dans PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
L'exportation d'un objet WORKSHEET vers un fichier TXT à partir d'une feuille de calcul est une tâche complexe. L'exportation des transitions de format WORKSHEET vers TXT est effectuée par notre SDK PHP tout en conservant le contenu structurel et logique principal de la feuille de calcul source WORKSHEET. Notre bibliothèque PHP est une solution professionnelle pour exporter en ligne des objets WORKSHEET vers des fichiers au format TXT. Ce SDK Cloud offre aux développeurs PHP des fonctionnalités puissantes et une sortie TXT parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans PHP utilisant REST API pour exporter WORKSHEET au format TXT à partir d\'une feuille de calcul" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'worksheet', 'txt' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser PHP API pour exporter WORKSHEET vers TXT" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode postExport pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>PHP 7.4 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
