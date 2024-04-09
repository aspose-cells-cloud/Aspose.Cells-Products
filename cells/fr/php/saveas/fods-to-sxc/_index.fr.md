---
title:  Enregistrez FODS en tant que SXC en utilisant PHP
description:  Utilisation du SDK Cloud Aspose.Cells pour PHP pour enregistrer le fichier au format FODS en tant que fichier au format SXC.
kwords: Excel, Save FODS as SXC, REST, PHP
howto: How to save FODS as SXC using Aspose.Cells Cloud PHP library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Enregistrer FODS en tant que SXC" h2="Bibliothèque PHP pour enregistrer FODS au format SXC" p="Utilisez SaveAs API sur Cells Cloud pour créer des flux de travail de feuilles de calcul personnalisés dans PHP. Il s\'agit d\'une solution professionnelle pour enregistrer les FODS au format SXC et d\'autres formats de documents en ligne à l\'aide de PHP." urlsection="saveas/fods-to-sxc/" >}}

{{< blocks/products/cells/cells-cloud-section title="Enregistrez un fichier FODS sous SXC dans PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Enregistrer les formats de fichiers de FODS au format SXC est une tâche complexe. Toutes les transitions du format FODS vers SXC sont effectuées par notre SDK PHP tout en conservant le contenu structurel et logique principal de la feuille de calcul FODS source. Notre bibliothèque PHP est une solution professionnelle pour enregistrer les FODS sous forme de fichiers SXC en ligne. Ce SDK Cloud offre aux développeurs PHP des fonctionnalités puissantes et une sortie SXC parfaite.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Exemple de code pour enregistrer FODS en tant que SXC à l\'aide de REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.fods';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "sxc";
    $newfilename = "Book1Saveas.sxc";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Découvrez comment enregistrer FODS au format SXC à l\'aide de la bibliothèque Cells Cloud PHP." >}}
<li> Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API</li>
<li>Installez la bibliothèque PHP et ajoutez la référence (importez la bibliothèque) à votre projet.</li>
<li>Ouvrez le fichier source en PHP.</li>
<li>Utilisez la méthode `PostWorkbookSaveAs` pour récupérer le flux résultant.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Configuration requise" >}}
<li>PHP 7.4 ou plus récent</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
