---
title: Exporter les Ods vers le fichier XLSX via PHP
description: Aspose.Cells Cloud REST API prend en charge l'exportation de fichiers Excel et d'objets internes vers des types de fichiers de format. Le SDK prend en charge différents types de langages de développement. Ils incluent Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby et Swift.
url: /fr/php/export/ods-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Exporter ODS vers un fichier XLSX dans le Cloud" h2="Excel et exportation de feuilles de calcul OpenOffice avec SDK Cloud open source pour PHP" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=" Exporter ODS vers le fichier XLSX dans le SDK Cloud pour PHP" %}}
1.  Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API
1. Initialisez ```CellsApi``` avec l'ID client, le secret client, l'URL de base et la version API
1. Appelez la méthode ```cellsWorkbookPutConvertWorkBook``` pour obtenir le flux XLSX résultant
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Commencez avec Excel REST API" %}}
 Obtenez le code source du SDK Cloud Excel for .NET à partir de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) pour compiler le SDK vous-même ou rendez-vous sur[Sorties](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/releases) pour des options de téléchargement alternatives.

 Jetez également un œil à Swagger-based[API Référence]() pour en savoir plus sur le[Excel REPOS API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Code pour la conversion ODS en XLSX" gistPath="" %}}
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.xlsx';    
    $format ='xlsx';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xlsx", 'w');
    fwrite($file,$content);
    fclose($file);
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
