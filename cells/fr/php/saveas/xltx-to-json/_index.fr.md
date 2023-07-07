---
title: Enregistrez XLTX sous JSON API pour PHP
description:  Utilisation du SDK Cloud Aspose.Cells pour PHP pour enregistrer le fichier au format XLTX en tant que fichier au format JSON.
url: /fr/php/saveas/xltx-to-json/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API pour enregistrer XLTX au format JSON" h2="Bibliothèque PHP pour enregistrer XLTX au format JSON" p="Utilisez Cells SaveAs REST API pour créer des flux de travail de feuille de calcul personnalisés dans PHP. Il s\'agit d\'une solution professionnelle pour enregistrer XLTX au format JSON et d\'autres formats de document en ligne à l\'aide de PHP." urlsection="saveas/xltx-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrer un fichier XLTX au format JSON en PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement de formats de fichiers à partir de XLTX au format JSON est une tâche complexe. Toutes les transitions de format XLTX vers JSON sont effectuées par notre SDK PHP tout en conservant le contenu structurel et logique principal de la feuille de calcul XLTX source. Notre bibliothèque PHP est une solution professionnelle pour enregistrer XLTX en tant que fichiers JSON en ligne. Ce SDK Cloud offre aux développeurs PHP des fonctionnalités puissantes et une sortie JSON parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans PHP utilisant REST API pour enregistrer XLTX au format JSON" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xltx';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "json";
    $newfilename = "Book1Saveas.json";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser PHP API pour enregistrer XLTX au format JSON" >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Initialiser CellsApi avec l'ID client, le secret client, l'URL de base et la version API</li>
<li>Appelez la méthode cellsSaveAsPostDocumentSaveAs pour obtenir le flux résultant</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>PHP 7.4 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
