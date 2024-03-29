﻿---
title:  Convertir FODS en XLTM via .NET
description: Créez, modifiez ou convertissez des fichiers Excel avec le SDK Cloud API et Open Source .NET
url: /fr/net/conversion/fods-to-xltm/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: XLTM
platform: .NET
otherformats: XLTX XML XPS XLTM XLSM TXT MHTML TIFF ODS CSV SVG MD XLSB TSV PDF FODS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir FODS en XLTM dans le cloud" h2="Excel et conversion de feuilles de calcul OpenOffice avec le SDK Cloud open source for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion FODS en XLTM dans les applications .NET" %}}
1.  Créez un compte sur<a href="https://dashboard.aspose.cloud/">Tableau de bord</a> pour obtenir gratuitement les détails du quota et de l'autorisation API
1. Initialisez ```CellsApi``` avec l'ID client, le secret client, l'URL de base et la version API
1. Téléchargez le fichier FODS sur Cloud Storage par défaut avec la méthode ```CellsApi.Upload```
1. Appelez la méthode ```CellsApi.CellsSaveAsPostDocumentSaveAs``` pour obtenir le fichier XLTM résultant
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Commencez avec Excel REST API" %}}
 Obtenez le code source du SDK Cloud Excel for .NET à partir de[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) pour compiler le SDK vous-même ou rendez-vous sur[Sorties](https://releases.aspose.cloud/) pour des options de téléchargement alternatives.

 Jetez également un œil à Swagger-based[API Référence](https://apireference.aspose.cloud/cells/) pour en savoir plus sur le[Excel REPOS API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET Code pour la conversion FODS en XLTM" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "xltm";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.xltm", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}