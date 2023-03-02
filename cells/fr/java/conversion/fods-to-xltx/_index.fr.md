---
title:  Convertir FODS en XLTX dans le Cloud via Java
description: Créer, modifier ou convertir des fichiers Excel avec REST API et Open Source Java SDK
url: /fr/java/conversion/fods-to-xltx/
family: cells
platformtag: java
feature: conversion
informat: FODS
outformat: XLTX
platform: Java
otherformats: ODS XLTM FODS XPS MHTML MD XLS TSV XLSB TXT XLSM XLSX XLTX CSV PDF SVG 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir FODS en XLTX avec Java" h2="Automatisez la conversion de fichiers Excel et OpenOffice avec le SDK Cloud open source for Java" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion simple FODS en XLTX" %}}
1.  Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API
1. Initialisez ```CellsApi``` avec l'ID client, le secret client, l'URL de base et la version API
1. Importer le fichier FODS dans Cloud Storage par défaut avec la méthode ```CellsApi.Upload```
1. Appelez le ```CellsApi.cellsWorkbookGetWorkbook``` pour obtenir le fichier XLTX résultant
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Démarrer avec Excel API & Java SDK" %}}
 Obtenez le code source Excel du SDK Cloud for Java à partir de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-java) pour compiler le SDK vous-même ou dirigez-vous vers le[Communiqués](https://releases.aspose.cloud/) pour les options de téléchargement alternatives.

 Jetez également un œil à Swagger[API Référence](https://apireference.aspose.cloud/cells/) pour en savoir plus sur la[Excel REPOS API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Code pour convertir FODS en XLTX" gistPath="" %}}
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
try {
    CellsApi api = new CellsApi(System.getenv("CellsCloudTestClientId"), System.getenv("CellsCloudTestClientSecret"), "v3.0", System.getenv("CellsCloudTestApiBaseUrl"));
    String name = BOOK1;
    String password = null;
    Boolean isAutoFit = true;
    Boolean onlySaveTable = true;
    String format = "XLTX";
    String folder = TEMPFOLDER;
    api.uploadFile( folder +"/"+ name, new File("c:\\TestData\\" + name) , null);
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