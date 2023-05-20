---
title:  Konvertera FODS till TSV via .NET
description: Skapa, redigera eller konvertera Excel-filer med Cloud API & Open Source .NET SDK
url: /sv/net/conversion/fods-to-tsv/
family: cells
platformtag: net
feature: conversion
informat: FODS
outformat: TSV
platform: .NET
otherformats: MHTML DIF ODS XPS XLS XLSX XLSM TXT TIFF TSV XLTM MD PDF CSV FODS XLSB 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertera FODS till TSV i molnet" h2="Excel & OpenOffice kalkylarkskonvertering med open source Cloud SDK for .NET" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="FODS till TSV-konvertering i .NET-appar" %}}
1.  Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation
1. Initiera ```CellsApi``` med klient-id, klienthemlighet, basadress och API-version
1. Ladda upp FODS-fil till standardmolnlagring med metoden ```CellsApi.Upload```
1. Ring ```CellsApi.CellsSaveAsPostDocumentSaveAs```-metoden för att få den resulterande TSV-filen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Kom igång med Excel REST API" %}}
 Få Excel Cloud SDK for .NET källkod från[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet) för att kompilera SDK själv eller gå till[Släpps](https://releases.aspose.cloud/) för alternativa nedladdningsalternativ.

 Ta också en titt på Swagger-baserad[API Referens](https://apireference.aspose.cloud/cells/) att veta mer om[Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# .NET Kod för FODS till TSV-konvertering" gistPath="" %}}
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