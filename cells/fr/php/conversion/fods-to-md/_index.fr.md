---
title:  Convertir FODS en MD dans le Cloud via PHP
description: Créer, modifier ou convertir des fichiers Excel avec REST API et Open Source PHP SDK
url: /fr/php/conversion/fods-to-md/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: MD
platform: PHP
otherformats: MD XLSX XPS TXT DIF MHTML XLTM CSV PDF XLSM TSV XLSB XML ODS XLTX SVG 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir FODS en MD avec PHP" h2="Automatisez la conversion de fichiers Excel et OpenOffice avec le SDK Cloud open source pour PHP" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Convertir rapidement FODS en MD via PHP" %}}
1.  Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API
1. Initialisez ```CellsApi``` avec l'ID client, le secret client, l'URL de base et la version API
1. Importer le fichier FODS dans Cloud Storage par défaut avec la méthode ```CellsApi.uploadFile```
1. Appelez le ```CellsApi.cellsSaveAsPostDocumentSaveAs``` pour obtenir le fichier MD résultant
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Démarrer avec Excel API & PHP SDK" %}}
 Obtenez le SDK Cloud Excel pour le code source PHP de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) pour compiler le SDK vous-même ou dirigez-vous vers le[Communiqués](https://releases.aspose.cloud/) pour les options de téléchargement alternatives.

 Jetez également un œil à Swagger[API Référence](https://apireference.aspose.cloud/cells/) pour en savoir plus sur la[Excel REPOS API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Code pour la conversion FODS en MD" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.md";
$isAutoFitRows= 'true';
$isAutoFitColumns= 'true';
$folder = "Temp";
CellsApi::ready( $this->instance, $name, $folder );
$result = $this->instance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename, $isAutoFitRows, $isAutoFitColumns, $folder);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}