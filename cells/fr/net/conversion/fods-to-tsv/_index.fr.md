---
title:  Convertir FODS en TSV via .NET
description: Créez, modifiez ou convertissez des fichiers Excel avec le SDK Cloud API et Open Source .NET
url: /fr/net/conversion/fods-to-tsv/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: TSV
platform: .NET
otherformats: MHTML DIF ODS XPS XLS XLSX XLSM TXT TIFF TSV XLTM MD PDF CSV FODS XLSB 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir FODS en TSV dans le cloud" h2="Excel et conversion de feuilles de calcul OpenOffice avec le SDK Cloud open source for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion FODS en TSV dans les applications .NET" %}}
1.  Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API
1. Initialisez ```CellsApi``` avec l'ID client, le secret client, l'URL de base et la version API
1. Téléchargez le fichier FODS sur Cloud Storage par défaut avec la méthode ```CellsApi.Upload```
1. Appelez la méthode ```CellsApi.CellsSaveAsPostDocumentSaveAs``` pour obtenir le fichier TSV résultant
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Commencez avec Excel REST API" %}}
 Obtenez le code source du SDK Cloud Excel for .NET à partir de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) pour compiler le SDK vous-même ou rendez-vous sur[Sorties](https://releases.aspose.cloud/) pour des options de téléchargement alternatives.

 Jetez également un œil à Swagger-based[API Référence](https://apireference.aspose.cloud/cells/) pour en savoir plus sur le[Excel REPOS API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET Code pour la conversion FODS en TSV" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "tsv";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.tsv", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}