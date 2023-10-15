---
title: Enregistrez NUMBERS au format SQL en utilisant PHP
description:  Utilisation du SDK Cloud Aspose.Cells pour PHP pour enregistrer le fichier au format NUMBERS en tant que fichier au format SQL.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Enregistrer les NUMÉROS au format SQL" h2="Bibliothèque PHP pour enregistrer des NUMBERS au format SQL" p="Utilisez SaveAs API de Cells Cloud pour créer des flux de travail de feuille de calcul personnalisés dans PHP. Il s\'agit d\'une solution professionnelle pour enregistrer des NUMÉROS au format SQL et d\'autres formats de document en ligne à l\'aide de PHP." urlsection="saveas/numbers-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier NUMBERS au format SQL dans PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de NUMBERS au format SQL est une tâche complexe. Toutes les transitions du format NUMBERS vers SQL sont effectuées par notre SDK PHP tout en conservant le contenu structurel et logique principal de la feuille de calcul NUMBERS source. Notre bibliothèque PHP est une solution professionnelle pour enregistrer des NUMBERS sous forme de fichiers SQL en ligne. Ce SDK Cloud offre aux développeurs PHP des fonctionnalités puissantes et une sortie SQL parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="PHP Exemple de code pour enregistrer NUMBERS au format SQL à l\'aide de REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.numbers';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "sql";
    $newfilename = "Book1Saveas.sql";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser le SDK Cloud Cells pour PHP afin d\'enregistrer les fichiers Excel sous d\'autres formats NUMBERS comme SQL" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialisez le Cells API avec votre ID client, votre secret client, votre URL de base et votre version API.</li>
<li>Utilisez la méthode `PostWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>PHP 7.4 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
