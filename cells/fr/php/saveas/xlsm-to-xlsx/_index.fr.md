﻿---
title:  Enregistrez XLSM sous XLSX API pour PHP
description:  API Cloud et SDK pour Microsoft Excel et OpenOffice Calc. Convertir une feuille de calcul en un autre format de fichier.
url: /fr/php/saveas/xlsm-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API pour enregistrer XLSM en XLSX" h2="PHP bibliothèque pour enregistrer XLSM en XLSX" p="Utilisez Cells SaveAs REST API pour créer des flux de travail de feuille de calcul personnalisés dans PHP. Il s\'agit d\'une solution professionnelle pour enregistrer XLSM au format XLSX et d\'autres formats de documents en ligne à l\'aide de PHP." urlsection="saveas/xlsm-to-xlsx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrez un fichier XLSM sous XLSX dans PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement des formats de fichiers de XLSM au format XLSX est une tâche complexe. Toutes les transitions de format XLSM vers XLSX sont effectuées par notre SDK PHP tout en conservant le contenu structurel et logique principal de la feuille de calcul XLSM source. Notre bibliothèque PHP est une solution professionnelle pour enregistrer en ligne des fichiers XLSM au format XLSX. Ce SDK Cloud offre aux développeurs PHP des fonctionnalités puissantes et une sortie XLSX parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans PHP utilisant REST API pour enregistrer XLSM au format XLSX" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xlsm';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "xlsx";
    $newfilename = "Book1Saveas.xlsx";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser PHP API pour enregistrer XLSM en XLSX" >}}
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