---
title:  Convertir FODS en XLSB sur Android
description: Automatisez les opérations de manipulation de fichiers Excel telles que la création, l'édition et la conversion avec Cloud API et le SDK Android Open Source
url: /fr/android/conversion/fods-to-xlsb/
family: cells
platformtag: android
feature: conversion
informat: FODS
outformat: XLSB
platform: Android
otherformats: TSV ODS XLSM FODS XLTX SVG XLSX XLSB DIF TXT CSV XPS XML XLTM HTML MHTML 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir FODS en XLSB dans le cloud" h2="Convertissez les feuilles de calcul Excel et OpenOffice avec le SDK Cloud open source pour Android" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion FODS en XLSB dans les applications Android" %}}
1.  Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API
1. Initialisez ```CellsApi``` avec l'ID client, le secret client, l'URL de base et la version API
1. Téléchargez le fichier FODS sur Cloud Storage par défaut avec la méthode ```CellsApiUtil.Upload```
1. Appelez le ```CellsApi.cellsWorkbookGetWorkbook``` pour obtenir le fichier XLSB résultant
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Commencez avec Excel REST API" %}}
 Obtenez le SDK Cloud Excel pour le code source ANDROID à partir de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-android) pour compiler le SDK vous-même ou rendez-vous sur[Sorties](https://releases.aspose.cloud/) pour des options de téléchargement alternatives.

 Jetez également un œil à Swagger-based[API Référence](https://apireference.aspose.cloud/cells/) pour en savoir plus sur le[Excel REPOS API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Android : conversion FODS en XLSB" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
try {
    CellsApi api = new CellsApi(CellsApiUtil.GetClientId(), CellsApiUtil.GetClientSecret(), CellsApiUtil.GetAPIVersion(), CellsApiUtil.GetBaseUrl());
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "XLSB";
    String folder = TEMPFOLDER;
    CellsApiUtil.Upload(api, folder, name);
    File response = api.cellsWorkbookGetWorkbook(name, password, format, isAutoFit, onlySaveTable, folder, null, null);
}
catch (Exception e) {
    e.printStackTrace();
}
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}