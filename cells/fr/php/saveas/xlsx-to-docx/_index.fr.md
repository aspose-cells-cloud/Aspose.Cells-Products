---
title:  Enregistrez XLSX sous DOCX API pour PHP
description:  Utilisation de Aspose.Cells Cloud SDK pour PHP pour enregistrer le fichier au format XLSX en tant que fichier au format DOCX.
url: /fr/php/saveas/xlsx-to-docx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API pour enregistrer XLSX au format DOCX" h2="Bibliothèque PHP pour enregistrer XLSX au format DOCX" p="Utilisez Cells SaveAs REST API pour créer des workflows de feuille de calcul personnalisés dans PHP. Il s\'agit d\'une solution professionnelle pour enregistrer XLSX au format DOCX et d\'autres formats de documents en ligne à l\'aide de PHP." urlsection="saveas/xlsx-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Enregistrer un fichier XLSX au format DOCX au PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
L'enregistrement de formats de fichiers à partir de XLSX en tant que DOCX est une tâche complexe. Toutes les transitions de format XLSX vers DOCX sont effectuées par notre SDK PHP tout en conservant le contenu structurel et logique principal de la feuille de calcul XLSX source. Notre bibliothèque PHP est une solution professionnelle pour enregistrer en ligne XLSX sous forme de fichiers DOCX. Ce SDK Cloud offre aux développeurs PHP des fonctionnalités puissantes et une sortie DOCX parfaite.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Exemple de code dans PHP utilisant REST API pour enregistrer XLSX au format DOCX" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xlsx';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "docx";
    $newfilename = "Book1Saveas.docx";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Comment utiliser PHP API pour enregistrer XLSX en tant que DOCX" >}}
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
