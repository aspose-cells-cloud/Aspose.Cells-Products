﻿---
title:  Converti FODS in MD via .NET
description: Crea, modifica o converti file Excel con Cloud API e Open Source .NET SDK
url: /it/net/conversion/fods-to-md/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: MD
platform: .NET
otherformats: CSV ODS XML XLTX TIFF DIF TXT XLSM XLTM MD HTML PDF XPS FODS MHTML SVG 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converti FODS in MD nel cloud" h2="Excel e conversione del foglio di calcolo OpenOffice con Cloud SDK open source for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversione da FODS a MD nelle app .NET" %}}
1.  Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente quota API e dettagli di autorizzazione
1. Inizializza ```CellsApi``` con ID client, segreto client, URL di base e versione API
1. Carica il file FODS nel Cloud Storage predefinito con il metodo ```CellsApi.Upload```
1. Chiama il metodo ```CellsApi.CellsSaveAsPostDocumentSaveAs``` per ottenere il file MD risultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Inizia con Excel REST API" %}}
 Ottieni il codice sorgente Excel Cloud SDK for .NET da[Git Hub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) per compilare tu stesso l'SDK o vai al file[Rilasci](https://releases.aspose.cloud/) per opzioni di download alternative.

 Dai anche un'occhiata a Swagger-based[API Riferimento](https://apireference.aspose.cloud/cells/) per saperne di più sul[Excel RIPOSO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET Codice per Conversione da FODS a MD" gistPath="" %}}
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
CellsApi instance = new CellsApi(clientId, clientSecret, apiVersion, baseurl);
string name = BOOK1;
SaveOptions saveOptions = new SaveOptions();
saveOptions.SaveFormat = "md";
instance.UploadFile(folder + @"\" + name, File.Open( @"C:\TestData\" +name), "DropBox");
var response = instance.CellsSaveAsPostDocumentSaveAs(name, saveOptions,  "output.md", null, null, folder, "DropBox");
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}