---
title:  Convertir FODS en HTML via .NET
description: Créer, modifier ou convertir des fichiers Excel avec Cloud API et Open Source .NET SDK
url: /fr/net/conversion/fods-to-html/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: HTML
platform: .NET
otherformats: XML XLT XLTM XLTX SVG XLSB TXT ODS TSV DIF PDF TIFF MD XLSM MHTML CSV 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir FODS en HTML dans le Cloud" h2="Excel et conversion de feuille de calcul OpenOffice avec le SDK Cloud open source for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion FODS en HTML dans les applications .NET" %}}
1.  Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API
1. Initialisez ```CellsApi``` avec l'ID client, le secret client, l'URL de base et la version API
1. Importer le fichier FODS dans Cloud Storage par défaut avec la méthode ```CellsApi.Upload```
1. Appelez la méthode ```CellsApi.CellsSaveAsPostDocumentSaveAs``` pour obtenir le fichier HTML résultant
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Démarrer avec Excel REST API" %}}
 Obtenez le code source Excel du SDK Cloud for .NET à partir de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) pour compiler le SDK vous-même ou dirigez-vous vers le[Communiqués](https://releases.aspose.cloud/) pour les options de téléchargement alternatives.

 Jetez également un œil à Swagger[API Référence](https://apireference.aspose.cloud/cells/) pour en savoir plus sur la[Excel REPOS API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET Code pour FODS à HTML Conversion" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "html";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.html", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}