---
title:  Convertissez XLTX en SVG en utilisant PHP
description:  Utilisation du SDK Cloud Aspose.Cells pour PHP pour convertir un fichier au format XLTX en fichier au format SVG.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir XLTX en SVG" h2="Bibliothèque PHP pour convertir XLTX en SVG" p="Utilisez la conversion API du cloud Cells pour créer des workflows de feuilles de calcul personnalisés dans les projets PHP. Il s\'agit d\'une solution professionnelle pour convertir XLTX en SVG et d\'autres formats de documents en ligne en utilisant PHP." urlsection="conversion/xltx-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convertissez XLTX en SVG à l\'aide du SDK Cloud Cells pour PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
La conversion des formats de fichiers de XLTX en SVG peut être une tâche complexe. Notre SDK PHP gère toutes les conversions du format XLTX vers SVG tout en préservant le contenu structurel et logique principal de la feuille de calcul XLTX source. Notre bibliothèque PHP fournit une solution professionnelle pour convertir en ligne XLTX en fichiers SVG. Ce SDK Cloud offre aux développeurs PHP des fonctionnalités puissantes et garantit une sortie SVG de haute qualité.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP Exemple de code pour convertir XLTX en SVG à l\'aide du SDK Cloud Cells" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xltx';    
    $format ='svg';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.svg", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour PHP pour convertir les fichiers Excel vers d\'autres formats XLTX en SVG" >}}
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
