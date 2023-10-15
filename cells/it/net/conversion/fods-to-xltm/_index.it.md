---
title:  Converti FODS in XLTM via .NET
description: Crea, modifica o converti file Excel con Cloud API e SDK Open Source .NET
url: /it/net/conversion/fods-to-xltm/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: XLTM
platform: .NET
otherformats: XLTX XML XPS XLTM XLSM TXT MHTML TIFF ODS CSV SVG MD XLSB TSV PDF FODS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converti FODS in XLTM nel Cloud" h2="Excel e conversione di fogli di calcolo OpenOffice con Cloud SDK open source for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversione da FODS a XLTM nelle app .NET" %}}
1.  Crea un account su<a href="https://dashboard.aspose.cloud/">Pannello di controllo</a> per ottenere gratuitamente la quota API e i dettagli dell'autorizzazione
1. Inizializza ```CellsApi``` con ID client, segreto client, URL di base e versione API
1. Carica il file FODS sul Cloud Storage predefinito con il metodo ```CellsApi.Upload```
1. Chiama il metodo ```CellsApi.CellsSaveAsPostDocumentSaveAs``` per ottenere il file XLTM risultante
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Inizia con Excel REST API" %}}
 Ottieni il codice sorgente Excel Cloud SDK for .NET da[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) per compilare tu stesso l'SDK o vai al file[Rilasci](https://releases.aspose.cloud/) per opzioni di download alternative.

 Dai un'occhiata anche a Swagger-based[API Riferimento](https://apireference.aspose.cloud/cells/) per saperne di più su[Excel RESTO API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET Codice per conversione da FODS a XLTM" gistPath="" %}}
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