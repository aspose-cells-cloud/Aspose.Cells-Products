---
title:  Convertissez BMP en XLSB en utilisant PHP
description:  Utilisation du SDK Cloud Aspose.Cells pour PHP pour convertir un fichier au format BMP en fichier au format XLSB.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir BMP en XLSB" h2="Bibliothèque PHP pour convertir BMP en XLSB" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets PHP. Il s\'agit d\'une solution professionnelle pour convertir BMP en XLSB et d\'autres formats de documents en ligne à l\'aide de PHP." urlsection="conversion/bmp-to-xlsb/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez BMP en XLSB à l’aide du SDK Cloud Cells pour PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de BMP en XLSB peut être une tâche complexe. Notre SDK PHP gère toutes les conversions du format BMP au format XLSB tout en préservant le contenu structurel et logique principal de la feuille de calcul source BMP. Notre bibliothèque PHP fournit une solution professionnelle pour convertir en ligne des fichiers BMP en fichiers XLSB. Ce SDK Cloud offre aux développeurs PHP des fonctionnalités puissantes et garantit une sortie XLSB de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP Exemple de code pour convertir BMP en XLSB à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.bmp';    
    $format ='xlsb';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xlsb", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour PHP afin de convertir les fichiers Excel vers d\'autres formats BMP en XLSB" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `putConvertWorkbook` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>PHP 7.4 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
