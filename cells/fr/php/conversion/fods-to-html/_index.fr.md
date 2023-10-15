---
title:  Convertir FODS en HTML dans le Cloud via PHP
description: Créez, modifiez ou convertissez des fichiers Excel avec le SDK REST API et Open Source PHP
url: /fr/php/conversion/fods-to-html/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: HTML
platform: PHP
otherformats: ODS TXT XLT XLSX XML CSV TSV MHTML FODS DIF XLSB XLTM PDF XLSM MD TIFF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertissez FODS en HTML avec PHP" h2="Automatisez la conversion de fichiers Excel et OpenOffice avec le SDK Cloud open source pour PHP" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Convertissez rapidement FODS en HTML via PHP" %}}
1.  Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API
1. Initialisez ```CellsApi``` avec l'ID client, le secret client, l'URL de base et la version API
1. Téléchargez le fichier FODS sur Cloud Storage par défaut avec la méthode ```CellsApi.uploadFile```
1. Appelez le ```CellsApi.cellsSaveAsPostDocumentSaveAs``` pour obtenir le fichier HTML résultant
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Premiers pas avec les SDK Excel, API et PHP" %}}
 Obtenez le SDK Cloud Excel pour le code source PHP à partir de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) pour compiler le SDK vous-même ou rendez-vous sur[Sorties](https://releases.aspose.cloud/) pour des options de téléchargement alternatives.

 Jetez également un œil à Swagger-based[API Référence](https://apireference.aspose.cloud/cells/) pour en savoir plus sur le[Excel REPOS API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Code pour la conversion FODS en HTML" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.html";
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